[26Oct2020 05:50:50.826] [main/INFO] [cpw.mods.modlauncher.Launcher/MODLAUNCHER]: ModLauncher running: args [--username, FireyAlex12, --version, 1.16.3-forge-34.1.27, --gameDir, C:\Users\alexn\AppData\Roaming\.minecraft, --assetsDir, C:\Users\alexn\AppData\Roaming\.minecraft\assets, --assetIndex, 1.16, --uuid, c3cc55c45f154a90ab639ce94cc068e3, -accessToken, ????????, --userType, mojang, --versionType, release, --launchTarget, fmlclient, --fml.forgeVersion, 34.1.27, --fml.mcVersion, 1.16.3, --fml.forgeGroup, net.minecraftforge, --fml.mcpVersion, 20200911.084530]
[26Oct2020 05:50:50.832] [main/INFO] [cpw.mods.modlauncher.Launcher/MODLAUNCHER]: ModLauncher 8.0.3+82+master.d2ed850 starting: java version 1.8.0_51 by Oracle Corporation
[26Oct2020 05:50:51.067] [main/INFO] [optifine.OptiFineTransformationService/]: OptiFineTransformationService.onLoad
[26Oct2020 05:50:51.069] [main/INFO] [optifine.OptiFineTransformationService/]: OptiFine ZIP file: C:\Users\alexn\AppData\Roaming\.minecraft\mods\OptiFine_1.16.3_HD_U_G3.jar
[26Oct2020 05:50:51.281] [main/INFO] [net.minecraftforge.fml.loading.FixSSL/CORE]: Added Lets Encrypt root certificates as additional trust
[26Oct2020 05:50:51.397] [main/INFO] [mixin/]: SpongePowered MIXIN Subsystem Version=0.8.2
Source=file:/C:/Users/alexn/AppData/Roaming/.minecraft/libraries/org/spongepowered/mixin/0.8.2/mixin-0.8.2.jar Service=ModLauncher Env=CLIENT
[26Oct2020 05:50:51.411] [main/INFO] [optifine.OptiFineTransformationService/]: OptiFineTransformationService.initialize
[26Oct2020 05:50:53.552] [main/INFO] [optifine.OptiFineTransformationService/]: OptiFineTransformationService.transformers
[26Oct2020 05:50:53.694] [main/INFO] [optifine.OptiFineTransformer/]: Targets: 311
[26Oct2020 05:50:54.265] [main/INFO] [optifine.OptiFineTransformationService/]: additionalClassesLocator: [optifine., net.optifine.]
[26Oct2020 05:50:54.518] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: java.lang.ExceptionInInitializerError[26Oct2020 05:50:54.518] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:275)
[26Oct2020 05:50:54.518] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:136)
[26Oct2020 05:50:54.519] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:98)
[26Oct2020 05:50:54.519] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:357)
[26Oct2020 05:50:54.519] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.lang.Class.forName0(Native Method)
[26Oct2020 05:50:54.520] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.lang.Class.forName(Class.java:348)
[26Oct2020 05:50:54.525] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.service.modlauncher.ModLauncherClassProvider.findClass(ModLauncherClassProvider.java:57)
[26Oct2020 05:50:54.525] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.platform.MixinConnectorManager.loadConnectors(MixinConnectorManager.java:71)
[26Oct2020 05:50:54.525] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.platform.MixinConnectorManager.inject(MixinConnectorManager.java:60)
[26Oct2020 05:50:54.525] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.platform.MixinPlatformManager.inject(MixinPlatformManager.java:197)
[26Oct2020 05:50:54.526] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.MixinBootstrap.inject(MixinBootstrap.java:190)
[26Oct2020 05:50:54.526] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.MixinLaunchPlugin.initializeLaunch(MixinLaunchPlugin.java:196)
[26Oct2020 05:50:54.533] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchPluginHandler.lambda$announceLaunch$9(LaunchPluginHandler.java:97)
[26Oct2020 05:50:54.533] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchPluginHandler$$Lambda$426/1956598686.accept(Unknown Source)
[26Oct2020 05:50:54.534] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.util.HashMap.forEach(HashMap.java:1280)
[26Oct2020 05:50:54.534] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchPluginHandler.announceLaunch(LaunchPluginHandler.java:97)
[26Oct2020 05:50:54.535] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:52)
[26Oct2020 05:50:54.535] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:72)
[26Oct2020 05:50:54.535] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.Launcher.run(Launcher.java:81)
[26Oct2020 05:50:54.535] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.Launcher.main(Launcher.java:65)
[26Oct2020 05:50:54.536] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: Caused by: java.lang.NoSuchFieldException: jv
[26Oct2020 05:50:54.537] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at java.lang.Class.getDeclaredField(Class.java:2070)
[26Oct2020 05:50:54.537] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.SecureJarHandler.lambda$static$3(SecureJarHandler.java:42)
[26Oct2020 05:50:54.537] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.SecureJarHandler$$Lambda$467/703644914.get(Unknown Source)
[26Oct2020 05:50:54.537] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.api.LamdbaExceptionUtils.uncheck(LamdbaExceptionUtils.java:95)
[26Oct2020 05:50:54.538] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.SecureJarHandler.<clinit>(SecureJarHandler.java:42)
[26Oct2020 05:50:54.538] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	... 20 more
