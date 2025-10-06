# Room Asset
Base Type: **C# Class**  
Interfaces: **ICloneable**

A class tracking saved values across the game.


## Static Fields

### current `(SaveFile)`
### deathReloadData `(SaveFile)`
### IO `(SaveFile.IOStream)`


## Fields

### location `Destination`
### playerStats `(SavedPlayerStats)`
### powerEggs `SavedCollectible`
### wishbones `SavedCollectible`
### hensRescured `SavedCollectible`
### globalChanges `SavedFlagSet`
### areaChanges `Dictionary<AreaAsset, Flags.SavedFlagSet>`

## Public Methods

### SaveFile()
### Clone(SaveFile)


## Public Static Methods

### RevertToDeathData()
### RevertToSaveFile()
### ApplyToSaveFile()
### SaveFileToDisk(Location)