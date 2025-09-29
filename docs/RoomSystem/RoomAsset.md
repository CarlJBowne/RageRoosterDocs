# Room Asset
Base Type: ScriptableObject

Stores the data and manages the state of a room.

## Serialized Fields

### displayName `(string)`
### area `(AreaAsset)`
### scene `(SceneReference)`
### lod `(RoomLOD)`
### transitions `(TransitionData[])`

## Data Fields

### root `(RoomRoot)`
### roomState `(RoomState)`
### currentLod `(int)`

## Public Methods

### `void Enter()`
### `void Update()`