``````````````````````````````````````````````````````````````````````````````````````````````````````````````

<Project Sdk="Microsoft.NET.Sdk.Web">

  <PropertyGroup>
    <TargetFramework>net6.0</TargetFramework>
    <Nullable>enable</Nullable>
    <ImplicitUsings>enable</ImplicitUsings>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="Microsoft.EntityFrameworkCore.Design" Version="6.0.26">
      <PrivateAssets>all</PrivateAssets>
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.EntityFrameworkCore.Sqlite" Version="6.0.26" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="6.0.26" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="6.0.26">
      <PrivateAssets>all</PrivateAssets>
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Design" Version="6.0.16" />
  </ItemGroup>

</Project>

````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
Scaffold-Dbcontext "Server=DESKTOP-QVPOJIS\SQLEXPRESS1; Database=CodeFirstDB; Trusted_Connection=True; TrustServerCertificate=True;"Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models

Scaffold-Dbcontext "Server=DESKTOP-QVPOJIS\SQLEXPRESS1; Database=CodeFirstDB; Trusted_Connection=True; TrustServerCertificate=True;"Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -force

````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
