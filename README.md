
![a-space-explorer-in-a-spacesuit-with-a-h_1ALIoLiAQ32tBX2Ni0GQ7g_tdvT0ifwTni0gVS0dwpGwg](https://github.com/user-attachments/assets/b3fb4c30-c83e-4807-b91f-aa8806b4a2e5)

<h1 align="center">
  <br />

  <br />
  <b>Space Explorer API</b>
  <br />
  <sub><sup><b>(SPACE-EXPLORER-API)</b></sup></sub>
  <br />
  <a
    href="https://github.com/yourUsername/SpaceExplorerAPI/actions/workflows/build.yml"
  >
  </a>
  <a href="https://github.com/yourUsername/SpaceExplorerAPI/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/yourUsername/SpaceExplorerAPI"
      alt="Latest Release"
    />
  </a>
</h1>

<p align="center">
  This .NET Core API is designed to serve JSON formatted data about celestial bodies and space missions. It is a backend service built with .NET Core 3.1 and various modern dependencies for data management and API response handling.
  <br />
</p>

<p align="center">
  Developed with Entity Framework Core and other modern .NET technologies, this project aims to provide a robust API for accessing space exploration data.
  <br />
</p>

<p align="center">
  <br />
  <img src="./_docs/assets/carbon.png" />
</p>

## API Endpoints

<table align="center">
  <tr>
    <th>Method</th>
    <th>Endpoint</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/celestial-bodies</td>
    <td>Returns a list of all celestial bodies</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/celestial-bodies/{id}</td>
    <td>Returns details of a specific celestial body by ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/celestial-bodies</td>
    <td>Endpoint to create a new celestial body entry</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/space-missions</td>
    <td>Returns a list of all space missions</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/space-missions/{id}</td>
    <td>Returns details of a specific space mission by ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/space-missions</td>
    <td>Endpoint to create a new space mission entry</td>
  </tr>
</table>

## Techniques Used

<p align="center">
  - <b>Entity Framework Core:</b> ORM for data management.<br />
  - <b>RESTful API Design:</b> Ensures clear and effective communication endpoints.<br />
  - <b>Dependency Injection:</b> Used throughout to promote loose coupling and enhanced testability.<br />
</p>

## Dependencies

<table align="center">
  <tr>
    <th>Package</th>
    <th>Version</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.Design</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.SqlServer</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td><a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a></td>
  </tr>
</table>

## :gear: Arch

```🌐
src
├── 📂 Controllers      [Routes for endpoints]
├── 📂 Models           [Database models]
├── 📂 Services         [Business rules]
├── 📂 Middlewares      [Intermediate functions between the HTTP request and the final server response]
├── 📂 Database         [Structures related to the database]
│   ├── 📂 DTOs             [Input Models and View Models (Data Transfer Objects)]
│   ├── 📂 EntityFramework  [Files related to the ORM Entity Framework]
│   │     ├── 📂 Context         [Entity context settings]
│   │     ├── 📂 Migrations      [Migrations for database updates]
│   ├── 📂 Repositories     [Repository pattern]
License
This software is licensed under the terms of the MIT License.

⌨️ PessOak - Github

