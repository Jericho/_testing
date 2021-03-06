# Information

- This report was generated by Cake.AddinDiscoverer DEBUG on Friday, June 1, 2018 at 6:52:02 PM GMT

# Statistics

- The analysis discovered 221 addins
  - 206 were successfully audited
  - 15 could not be audited (see the 'Exceptions' section)

- Of the 206 audited addins:
  - 105 are using the cake-contrib icon
  - 158 have a YAML file on the cake web site
  - 94 have been transfered to the cake-contrib organisation

# Reports

- Click [here](Audit_for_Cake_0.26.0.md) to view the report for Cake 0.26.0.
- Click [here](Audit_for_Cake_0.28.0.md) to view the report for Cake 0.28.0.

# Additional audit results

Due to space constraints we couldn't fit all audit information in this report so we generated an Excel spreadsheet that contains the following additional information:
- The `Maintainer` column indicates who is maintaining the source for this project
- The `Icon` column indicates if the nuget package for your addin uses the cake-contrib icon.
- The `YAML` column indicates if there is a `.yml` file describing the addin in this [repo](https://github.com/cake-build/website/tree/develop/addins).
- The `Transferred to cake-contrib` column indicates if the project has been moved to the cake-contrib github organisation.

Click [here](Audit.xlsx) to download the Excel spreadsheet.


# Exceptions

**Cake.AzureBlobStorage**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.CachedNpm**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.ClickTwice**: DownloadProjectFilesAsync: repos/agc93/clicktwice/contents/src/ClickTwice.Handlers.Core/ClickTwice.Handlers.Core.csproj was not found.
DownloadProjectFilesAsync: repos/agc93/clicktwice/contents/src/ClickTwice.Templates.SolidState.Package/ClickTwice.Templates.SolidState.Package.csproj was not found.
This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.FtpDeploy**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.GithubUtility**: This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.Intellisense**: This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.Issues.Testing**: The project does not exist: https://github.com/cake-contrib/Cake.Issues.Testing
This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.Packages**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.Parallel.Module**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.ServiceOrchestration**: This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.SimpleVersionIncrement**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.Sitecore**: FindSolutionPathAsync: Object reference not set to an instance of an object.
This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.SquareLogo**: We were unable to determine the Github repo URL. Most likely this means that the PackageProjectUrl is missing from the csproj.

**Cake.StyleCop**: DownloadProjectFilesAsync: repos/Ashthos/Cake.StyleCop/contents/Cake.Stylecop/Cake.Stylecop.csproj was not found.
This addin seem to be referencing neither Cake.Core nor Cake.Common.

**Cake.XmlDocMarkdown**: FindReferencesAsync: Value cannot be null.
Parameter name: path
FindFrameworksAsync: Value cannot be null.
Parameter name: path

