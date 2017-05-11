---
summary: Precompiles an ASP.NET application.
remarks: "ASP.NET supports three forms of precompilation. One form allows for the in-place precompilation of an ASP.NET application. In this form, the site is deployed to production and then precompiled, which eliminates the need to dynamically compile the site when it is first visited by a user. The first user of the site will not experience the delay normally encountered on a site that is dynamically compiled.  \n  \n The two other forms of precompilation are used for deployment. In either form, a layout of the site is generated that can be deployed to a production computer. One of these forms includes the markup pages so some amount of updating can be performed on the compiled site. The other form does not contain the markup pages and therefore cannot be updated without recompiling the original site. No source code is deployed to the target environment in either of these forms of precompilation.  \n  \n The application to precompile is defined through the <xref:System.Web.Compilation.ClientBuildManager> constructor. The <xref:System.Web.Compilation.ClientBuildManagerParameter> object of the <xref:System.Web.Compilation.ClientBuildManager.%23ctor%2A> constructor defines which of the three forms of precompilation to perform.  \n  \n A developer can precompile a Web site with the `aspnet_compiler` command-line tool or by calling the <xref:System.Web.Compilation.ClientBuildManager.PrecompileApplication%2A> method."
uid: System.Web.Compilation.ClientBuildManager.PrecompileApplication*
---