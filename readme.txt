File cannot be installed on 2022 as mentioned on github. It only works on 2017 and 2019.

11/16/2021 5:52:37 PM - Microsoft VSIX Installer
11/16/2021 5:52:37 PM - -------------------------------------------
11/16/2021 5:52:37 PM - vsixinstaller.exe version:
11/16/2021 5:52:37 PM - 17.0.5226-preview5
11/16/2021 5:52:37 PM - -------------------------------------------
11/16/2021 5:52:37 PM - Command line parameters:
11/16/2021 5:52:37 PM - C:\Program Files (x86)\Microsoft Visual Studio\Installer\resources\app\ServiceHub\Services\Microsoft.VisualStudio.Setup.Service\VSIXInstaller.exe,C:\Users\Sage\Downloads\DiscordRPforVS-5.5.4.vsix
11/16/2021 5:52:37 PM - -------------------------------------------
11/16/2021 5:52:37 PM - Microsoft VSIX Installer
11/16/2021 5:52:37 PM - -------------------------------------------
11/16/2021 5:52:38 PM - Initializing Install...
11/16/2021 5:52:38 PM - Extension Details...
11/16/2021 5:52:38 PM - 	Identifier         : VisualDevelopment.drpcvs
11/16/2021 5:52:38 PM - 	Name               : Discord Rich Presence
11/16/2021 5:52:38 PM - 	Author             : 1TheNikita
11/16/2021 5:52:38 PM - 	Version            : 5.5.4
11/16/2021 5:52:38 PM - 	Description        : A Discord Rich Presence extension for Visual Studio 2017 and 2019.
11/16/2021 5:52:38 PM - 	Locale             : en-US
11/16/2021 5:52:38 PM - 	MoreInfoURL        : https://marketplace.visualstudio.com/items?itemName=1TheNikita.drpcvs2019
11/16/2021 5:52:38 PM - 	InstalledByMSI     : False
11/16/2021 5:52:38 PM - 	SupportedFrameworkVersionRange : [4.5,)
11/16/2021 5:52:38 PM - 
11/16/2021 5:52:38 PM - 	SignatureState     : Unsigned
11/16/2021 5:52:38 PM - 	Supported Products : 
11/16/2021 5:52:38 PM - 		Microsoft.VisualStudio.Community
11/16/2021 5:52:38 PM - 			Version : [15.0,)
11/16/2021 5:52:38 PM - 			ProductArchitecture : x86
11/16/2021 5:52:38 PM - 		Microsoft.VisualStudio.Enterprise
11/16/2021 5:52:38 PM - 			Version : [15.0,)
11/16/2021 5:52:38 PM - 			ProductArchitecture : x86
11/16/2021 5:52:38 PM - 		Microsoft.VisualStudio.Pro
11/16/2021 5:52:38 PM - 			Version : [15.0,)
11/16/2021 5:52:38 PM - 			ProductArchitecture : x86
11/16/2021 5:52:38 PM - 
11/16/2021 5:52:38 PM - 	References         : 
11/16/2021 5:52:38 PM - 	Prerequisites      : 
11/16/2021 5:52:38 PM - 		-------------------------------------------------------
11/16/2021 5:52:38 PM - 		Identifier   : Microsoft.VisualStudio.Component.CoreEditor
11/16/2021 5:52:38 PM - 		Name         : Visual Studio core editor
11/16/2021 5:52:38 PM - 		Version      : [15.0,)
11/16/2021 5:52:38 PM - 
11/16/2021 5:52:38 PM - Signature Details...
11/16/2021 5:52:38 PM - 	Extension is not signed.
11/16/2021 5:52:38 PM - 
11/16/2021 5:52:38 PM - Searching for applicable products...
11/16/2021 5:52:38 PM - Found installed product - Global Location
11/16/2021 5:52:38 PM - Found installed product - Visual Studio Community 2022 Current
11/16/2021 5:52:38 PM - VSIXInstaller.NoApplicableSKUsException: This extension is not installable on any currently installed products.
   at VSIXInstaller.ExtensionService.GetInstallableDataImpl(IInstallableExtension extension, String extensionPackParentName, Boolean isRepairSupported, IStateData stateData, IEnumerable`1& skuData)
   at VSIXInstaller.ExtensionService.GetInstallableData(String vsixPath, String extensionPackParentName, Boolean isRepairSupported, IStateData stateData, IEnumerable`1& skuData)
   at VSIXInstaller.ExtensionPackService.IsExtensionPack(IStateData stateData, Boolean isRepairSupported)
   at VSIXInstaller.ExtensionPackService.ExpandExtensionPackToInstall(IStateData stateData, Boolean isRepairSupported)
   at VSIXInstaller.App.Initialize(Boolean isRepairSupported)
   at VSIXInstaller.App.Initialize()
   at System.Threading.Tasks.Task`1.InnerInvoke()
   at System.Threading.Tasks.Task.Execute()
--- End of stack trace from previous location where exception was thrown ---
   at Microsoft.VisualStudio.Telemetry.WindowsErrorReporting.WatsonReport.GetClrWatsonExceptionInfo(Exception exceptionObject)
