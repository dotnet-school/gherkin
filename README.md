### Requirements

- [ ] stable and well supported gherkin parser
- [ ] xunit support
- [ ] .NET core on macOS, Linux support
- [ ] IDE support for navigation to steps (VSCode, VStudio for Mac and Win and Rider)
- [ ] Report unused step and refactor steps from IDE (good to have)



### Solutions to asses

- [x] Specflow
- [ ] Xunit.Gherkin
- [ ] Try a custom parser (check for IDE support)



### Trying specflow from template 

```bash
# Install specflow template: 
dotnet new -i SpecFlow.Templates.DotNet
 
# Create new project using template with xunit
dotnet new specflowproject --unittestprovider xunit --framework netcoreapp3.1 

# Validate build
dotnet build
```

<span style="color: red" >Did not work, not even with dockerfile.</span>



Try https://www.nuget.org/packages/Xunit.Gherkin.Quick/ 

