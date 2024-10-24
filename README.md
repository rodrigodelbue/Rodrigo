# Rodrigo
Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio Version 17
VisualStudioVersion = 17.0.32014.148
MinimumVisualStudioVersion = 10.0.40219.1
Project("{2150E333-8FDC-42A3-9474-1A3956D46DE8}") = "src", "src", "{10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}"
EndProject
Project("{2150E333-8FDC-42A3-9474-1A3956D46DE8}") = "tests", "tests", "{B8D49C5A-37C3-4171-BD0A-9E7DAF889055}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.UnitTests", "tests\FC.Codeflix.Catalog.UnitTests\FC.Codeflix.Catalog.UnitTests.csproj", "{3B2BADC3-03BE-4F4D-8A27-92C309EAC0BF}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.Domain", "src\FC.Codeflix.Catalog.Domain\FC.Codeflix.Catalog.Domain.csproj", "{C6EC7AA6-0BA0-4300-9044-62F8A2C5B113}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.Application", "src\FC.Codeflix.Catalog.Application\FC.Codeflix.Catalog.Application.csproj", "{913E1182-0035-44F6-AB2B-AAF133482554}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.IntegrationTests", "tests\FC.Codeflix.Catalog.IntegrationTests\FC.Codeflix.Catalog.IntegrationTests.csproj", "{6558FA5A-75A8-4442-87F3-0C37D96D3984}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.Infra.Data.EF", "src\FC.Codeflix.Catalog.Infra.Data.EF\FC.Codeflix.Catalog.Infra.Data.EF.csproj", "{639C7F2C-74D7-4656-85C2-7627549429CB}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.EndToEndTests", "tests\FC.Codeflix.Catalog.EndToEndTests\FC.Codeflix.Catalog.EndToEndTests.csproj", "{F4B6781B-7865-4760-A7E8-EDA70519CBD4}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.Api", "src\FC.Codeflix.Catalog.Api\FC.Codeflix.Catalog.Api.csproj", "{67EC0BA2-7FE3-4FFF-8791-98E560C60EF9}"
EndProject
Project("{2150E333-8FDC-42A3-9474-1A3956D46DE8}") = "env", "env", "{E8A8A573-F592-4810-A5BB-95FC9FB45841}"
	ProjectSection(SolutionItems) = preProject
		docker-compose.yml = docker-compose.yml
	EndProjectSection
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.Infra.Storage", "src\FC.Codeflix.Catalog.Infra.Storage\FC.Codeflix.Catalog.Infra.Storage.csproj", "{85B0BE60-5E13-4294-A57F-79D0F092D3D0}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "FC.Codeflix.Catalog.Infra.Messaging", "src\FC.Codeflix.Catalog.Infra.Messaging\FC.Codeflix.Catalog.Infra.Messaging.csproj", "{DF2EC9BE-A1C2-4B2D-8179-420DC7F4D731}"
EndProject
Project("{2150E333-8FDC-42A3-9474-1A3956D46DE8}") = "Solution Items", "Solution Items", "{A715BA14-A527-45C9-B466-A48E5C191E58}"
	ProjectSection(SolutionItems) = preProject
		.github\workflows\ci.yml = .github\workflows\ci.yml
	EndProjectSection
EndProject
Global
	GlobalSection(SolutionConfigurationPlatforms) = preSolution
		Debug|Any CPU = Debug|Any CPU
		Release|Any CPU = Release|Any CPU
	EndGlobalSection
	GlobalSection(ProjectConfigurationPlatforms) = postSolution
		{3B2BADC3-03BE-4F4D-8A27-92C309EAC0BF}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{3B2BADC3-03BE-4F4D-8A27-92C309EAC0BF}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{3B2BADC3-03BE-4F4D-8A27-92C309EAC0BF}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{3B2BADC3-03BE-4F4D-8A27-92C309EAC0BF}.Release|Any CPU.Build.0 = Release|Any CPU
		{C6EC7AA6-0BA0-4300-9044-62F8A2C5B113}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{C6EC7AA6-0BA0-4300-9044-62F8A2C5B113}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{C6EC7AA6-0BA0-4300-9044-62F8A2C5B113}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{C6EC7AA6-0BA0-4300-9044-62F8A2C5B113}.Release|Any CPU.Build.0 = Release|Any CPU
		{913E1182-0035-44F6-AB2B-AAF133482554}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{913E1182-0035-44F6-AB2B-AAF133482554}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{913E1182-0035-44F6-AB2B-AAF133482554}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{913E1182-0035-44F6-AB2B-AAF133482554}.Release|Any CPU.Build.0 = Release|Any CPU
		{6558FA5A-75A8-4442-87F3-0C37D96D3984}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{6558FA5A-75A8-4442-87F3-0C37D96D3984}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{6558FA5A-75A8-4442-87F3-0C37D96D3984}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{6558FA5A-75A8-4442-87F3-0C37D96D3984}.Release|Any CPU.Build.0 = Release|Any CPU
		{639C7F2C-74D7-4656-85C2-7627549429CB}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{639C7F2C-74D7-4656-85C2-7627549429CB}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{639C7F2C-74D7-4656-85C2-7627549429CB}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{639C7F2C-74D7-4656-85C2-7627549429CB}.Release|Any CPU.Build.0 = Release|Any CPU
		{F4B6781B-7865-4760-A7E8-EDA70519CBD4}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{F4B6781B-7865-4760-A7E8-EDA70519CBD4}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{F4B6781B-7865-4760-A7E8-EDA70519CBD4}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{F4B6781B-7865-4760-A7E8-EDA70519CBD4}.Release|Any CPU.Build.0 = Release|Any CPU
		{67EC0BA2-7FE3-4FFF-8791-98E560C60EF9}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{67EC0BA2-7FE3-4FFF-8791-98E560C60EF9}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{67EC0BA2-7FE3-4FFF-8791-98E560C60EF9}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{67EC0BA2-7FE3-4FFF-8791-98E560C60EF9}.Release|Any CPU.Build.0 = Release|Any CPU
		{85B0BE60-5E13-4294-A57F-79D0F092D3D0}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{85B0BE60-5E13-4294-A57F-79D0F092D3D0}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{85B0BE60-5E13-4294-A57F-79D0F092D3D0}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{85B0BE60-5E13-4294-A57F-79D0F092D3D0}.Release|Any CPU.Build.0 = Release|Any CPU
		{DF2EC9BE-A1C2-4B2D-8179-420DC7F4D731}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{DF2EC9BE-A1C2-4B2D-8179-420DC7F4D731}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{DF2EC9BE-A1C2-4B2D-8179-420DC7F4D731}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{DF2EC9BE-A1C2-4B2D-8179-420DC7F4D731}.Release|Any CPU.Build.0 = Release|Any CPU
	EndGlobalSection
	GlobalSection(SolutionProperties) = preSolution
		HideSolutionNode = FALSE
	EndGlobalSection
	GlobalSection(NestedProjects) = preSolution
		{3B2BADC3-03BE-4F4D-8A27-92C309EAC0BF} = {B8D49C5A-37C3-4171-BD0A-9E7DAF889055}
		{C6EC7AA6-0BA0-4300-9044-62F8A2C5B113} = {10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}
		{913E1182-0035-44F6-AB2B-AAF133482554} = {10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}
		{6558FA5A-75A8-4442-87F3-0C37D96D3984} = {B8D49C5A-37C3-4171-BD0A-9E7DAF889055}
		{639C7F2C-74D7-4656-85C2-7627549429CB} = {10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}
		{F4B6781B-7865-4760-A7E8-EDA70519CBD4} = {B8D49C5A-37C3-4171-BD0A-9E7DAF889055}
		{67EC0BA2-7FE3-4FFF-8791-98E560C60EF9} = {10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}
		{85B0BE60-5E13-4294-A57F-79D0F092D3D0} = {10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}
		{DF2EC9BE-A1C2-4B2D-8179-420DC7F4D731} = {10E8B22D-64A7-4BA0-A7AE-C3B05FCE73C6}
	EndGlobalSection
	GlobalSection(ExtensibilityGlobals) = postSolution
		SolutionGuid = {A771D141-5397-4700-82B3-571A42CA3633}
	EndGlobalSection
EndGlobal
