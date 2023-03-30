## .NET/C# with React.js and TypeScript

Full stack bootstrap and publishing learning.

### Steps

1. Create directory for the entire project and cd into it
2. Install locally in project directory create-react-app (not globally!)
3. Create React App `yarn create-react-app client --template typescript`. Makue sure it's in `client` directory.
4. Go back to project directory and create new solution `dotnet new sln -n net-react`
5. While still in project directory create new folder named `web-api`
6. Open Rider/Visual Studio and create new .Net Core web app in `web-api` directory
7. Go back to project director and add web-api to main solution `dotnet sln net-react.sln add web-api/net-react-web.api.csproj`
8. Add fallback controller to web-api solution
9. Add Startup.cs to web-api solution
