# ogarindex.io
// serverLogLevel: Logging level of the server. 0 = No logs, 1 = Logs the console, 2 = Logs console and ip connections
 serverMaxConnections = 64
 serverPort = 443
-serverGamemode = 0
+serverGamemode = 2
 serverBots = 0
 serverViewBaseX = 1024
 serverViewBaseY = 592
 @@ -28,22 +28,22 @@ borderBottom = 6000
 // [Spawn]
 // Each interval is 1 tick (50 ms)
 spawnInterval = 20
-foodSpawnAmount = 10
+foodSpawnAmount = 100
 foodStartAmount = 100
-foodMaxAmount = 500
-foodMass = 1
+foodMaxAmount = 1000
+foodMass = 50
 virusMinAmount = 10
 virusMaxAmount = 50
 virusStartMass = 100
-virusFeedAmount = 7
+virusFeedAmount = 1
 
 // [Ejected Mass]
 // ejectMass: Mass of ejected cells
 // ejectMassLoss: Mass lost when ejecting cells
 // ejectSpeed: Base speed of ejected cells
 // ejectSpawnPlayer: Chance for a player to spawn from ejected mass
-ejectMass = 12
-ejectMassLoss = 16
+ejectMass = 50
+ejectMassLoss = 0
 ejectSpeed = 160
 ejectSpawnPlayer = 50
 
 @@ -52,14 +52,14 @@ ejectSpawnPlayer = 50
 // playerMassDecayRate: Amount of mass lost per tick (Multiplier) (1 tick = 1000 milliseconds)
 // playerMinMassDecay: Minimum mass for decay to occur
 // playerDisconnectTime: The amount of seconds it takes for a player cell to be removed after disconnection (If set to -1, cells are never removed)
-playerStartMass = 10
-playerMaxMass = 22500
+playerStartMass = 500
+playerMaxMass = 50000
 playerMinMassEject = 32
 playerMinMassSplit = 36
-playerMaxCells = 16
-playerRecombineTime = 30
-playerMassDecayRate = .002
-playerMinMassDecay = 9
+playerMaxCells = 50
+playerRecombineTime = 2
+playerMassDecayRate = .0000001
+playerMinMassDecay = 0
 playerMaxNickLength = 15
 playerDisconnectTime = 60
