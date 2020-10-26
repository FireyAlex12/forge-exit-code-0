[26Oct2020 03:08:25.855] [main/INFO] [net.minecraftforge.fml.loading.FixSSL/CORE]: Added Lets Encrypt root certificates as additional trust
[26Oct2020 03:08:25.939] [main/INFO] [mixin/]: SpongePowered MIXIN Subsystem Version=0.8.2 Source=file:/C:/Users/alexn/AppData/Roaming/.minecraft/libraries/org/spongepowered/mixin/0.8.2/mixin-0.8.2.jar Service=ModLauncher Env=CLIENT
[26Oct2020 03:08:25.950] [main/INFO] [optifine.OptiFineTransformationService/]: OptiFineTransformationService.initialize
[26Oct2020 03:08:28.138] [main/INFO] [optifine.OptiFineTransformationService/]: OptiFineTransformationService.transformers
[26Oct2020 03:08:28.268] [main/INFO] [optifine.OptiFineTransformer/]: Targets: 311
[26Oct2020 03:08:28.976] [main/INFO] [optifine.OptiFineTransformationService/]: additionalClassesLocator: [optifine., net.optifine.]
[26Oct2020 03:08:29.206] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: java.lang.ExceptionInInitializerError
[26Oct2020 03:08:29.206] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:275)
[26Oct2020 03:08:29.206] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:136)
[26Oct2020 03:08:29.207] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:98)
[26Oct2020 03:08:29.207] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:357)
[26Oct2020 03:08:29.207] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.lang.Class.forName0(Native Method)
[26Oct2020 03:08:29.207] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.lang.Class.forName(Class.java:348)
[26Oct2020 03:08:29.214] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.service.modlauncher.ModLauncherClassProvider.findClass(ModLauncherClassProvider.java:57)
[26Oct2020 03:08:29.214] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.platform.MixinConnectorManager.loadConnectors(MixinConnectorManager.java:71)
[26Oct2020 03:08:29.214] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.platform.MixinConnectorManager.inject(MixinConnectorManager.java:60)
[26Oct2020 03:08:29.215] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.platform.MixinPlatformManager.inject(MixinPlatformManager.java:197)
[26Oct2020 03:08:29.215] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.MixinBootstrap.inject(MixinBootstrap.java:190)
[26Oct2020 03:08:29.215] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at org.spongepowered.asm.launch.MixinLaunchPlugin.initializeLaunch(MixinLaunchPlugin.java:196)
[26Oct2020 03:08:29.223] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchPluginHandler.lambda$announceLaunch$9(LaunchPluginHandler.java:97)
[26Oct2020 03:08:29.223] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchPluginHandler$$Lambda$430/1956598686.accept(Unknown Source)
[26Oct2020 03:08:29.223] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at java.util.HashMap.forEach(HashMap.java:1280)
[26Oct2020 03:08:29.224] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchPluginHandler.announceLaunch(LaunchPluginHandler.java:97)
[26Oct2020 03:08:29.224] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:52)
[26Oct2020 03:08:29.224] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:72)
[26Oct2020 03:08:29.227] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.Launcher.run(Launcher.java:81)
[26Oct2020 03:08:29.227] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1052]: 	at cpw.mods.modlauncher.Launcher.main(Launcher.java:65)
[26Oct2020 03:08:29.227] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: Caused by: java.lang.NoSuchFieldException: jv
[26Oct2020 03:08:29.228] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at java.lang.Class.getDeclaredField(Class.java:2070)
[26Oct2020 03:08:29.228] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.SecureJarHandler.lambda$static$3(SecureJarHandler.java:42)
[26Oct2020 03:08:29.228] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.SecureJarHandler$$Lambda$474/703644914.get(Unknown Source)
[26Oct2020 03:08:29.228] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.api.LamdbaExceptionUtils.uncheck(LamdbaExceptionUtils.java:95)
[26Oct2020 03:08:29.255] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	at cpw.mods.modlauncher.SecureJarHandler.<clinit>(SecureJarHandler.java:42)
[26Oct2020 03:08:29.255] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:1061]: 	... 20 more
