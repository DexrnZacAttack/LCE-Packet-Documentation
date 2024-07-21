## Clientbound
| Packet Name                        | Packet ID | Notes                              |
| ---------------------------------- | ---------- | ---------------------------------- |
| KeepAlivePacket                    | 0x00       |                                    |
| LoginPacket                        | 0x01       |                                    |
| PreLoginPacket                     | 0x02       |                                    |
| ChatPacket                         | 0x03       |                                    |
| SetTimePacket                      | 0x04       |                                    |
| SetEquippedItemPacket              | 0x05       |                                    |
| SetSpawnPositionPacket             | 0x06       |                                    |
| SetHealthPacket                    | 0x08       |                                    |
| RespawnPacket                      | 0x09       |                                    |
| SetCarriedItemPacket               | 0x10       |                                    |
| PlayerSleepPacket                  | 0x11       |                                    |
| AnimatePacket                      | 0x12       |                                    |
| AddPlayerPacket                    | 0x14       |                                    |
| TakeItemEntityPacket               | 0x16       |                                    |
| AddEntityPacket                    | 0x17       |                                    |
| AddMobPacket                       | 0x18       |                                    |
| AddPaintingPacket                  | 0x19       |                                    |
| AddExperienceOrbPacket             | 0x1A       |                                    |
| SetEntityMotionPacket              | 0x1C       |                                    |
| RemoveEntitiesPacket               | 0x1D       |                                    |
| MoveEntityPacket                   | 0x1E       |                                    |
| MoveEntityPacketPos                | 0x1F       | ClientboundMoveEntityPacket::Pos   |
| MoveEntityPacketRot                | 0x20       | ClientboundMoveEntityPacket::Rot   |
| MoveEntityPacketPosRot             | 0x21       | ClientboundMoveEntityPacket::PosRot|
| TeleportEntityPacket               | 0x22       |                                    |
| RotateHeadPacket                   | 0x23       |                                    |
| EntityEventPacket                  | 0x26       |                                    |
| SetEntityLinkPacket                | 0x27       |                                    |
| SetEntityDataPacket                | 0x28       |                                    |
| UpdateAttributesPacket             | 0x2C       |                                    |
| SetExperiencePacket                | 0x2B       |                                    |
| RemoveMobEffectPacket              | 0x2A       |                                    |
| UpdateMobEffectPacket              | 0x29       |                                    |
| PowerupPacket                      | 0xAB       |                                    |
| BossEventPacket                    | 0x8B       |                                    |
| MoveVehiclePacket                  | 0x85       |                                    |
| BlockEntityDataPacket              | 0x84       |                                    |
| SoundPacket                        | 0x3E       |                                    |
| ExplodePacket                      | 0x3C       |                                    |
| LevelEventPacket                   | 0x3D       |                                    |
| LevelParticlesPacket               | 0x3F       |                                    |
| BlockUpdatePacket                  | 0x35       |                                    |
| BlockEventPacket                   | 0x36       |                                    |
| BlockDestructionPacket             | 0x37       |                                    |
| ChunkBlocksUpdatePacket            | 0x34       |                                    |
| AddGlobalEntityPacket              | 0x47       |                                    |
| GameEventPacket                    | 0x46       |                                    |
| ContainerOpenPacket                | 0x64       |                                    |
| ContainerClosePacket               | 0x65       |                                    |
| ContainerSetSlotPacket             | 0x67       |                                    |
| ContainerSetDataPacket             | 0x69       |                                    |
| ContainerSetContentPacket          | 0x68       |                                    |
| ContainerAckPacket                 | 0x6A       |                                    |
| SetPassengersPacket                | 0x86       |                                    |
| CustomPayloadPacket                | 0xFA       |                                    |
| ChangeDifficultyPacket             | 0xFD       |                                    |
| MapItemDataPacket                  | 0xD3       |                                    |
| OpenSignEditorPacket               | 0xD4       |                                    |
| PlayerCombatPacket                 | 0xD5       |                                    |
| PlayerPositionPacket               | 0xD6       |                                    |
| SetPlayerTeamPacket                | 0xD1       |                                    |
| ResourcePackPacket                 | 0xD8       |                                    |
| SetTitlesPacket                    | 0xDB       |                                    |
| TabListPacket                      | 0xDC       |                                    |
| CooldownPacket                     | 0xEC       |                                    |
| MGPlayerSettingsUpdatePacket       | 0xEF       |                                    |
| BlockCollectionDestructionPacket   | 0xEB       |                                    |
| DamageIndicatorPacket              | 0xEA       |                                    |

<!--
AcceptTeleportationPacket 0x87
ChatAutoCompletePacket 0xDD
ChatPacket 0xDE
ClientCommandPacket 0xCD
ContainerAckPacket 0xDF
ContainerButtonClickPacket 0x6C
ContainerClickPacket 0x66
ContainerClosePacket 0xE0
CustomPayloadPacket 0xE1
InteractPacket 0x07
KeepAlivePacket 0xE2
MovePlayerPacketPos 0x0B
MovePlayerPacketPosRot 0x0D
MovePlayerPacketRot 0x0C
MovePlayerPacket 0x0A
MoveVehiclePacket 0x88
PaddleBoatPacket 0x8A
PlayerAbilitiesPacket 0xE3
PlayerActionPacket 0x0E
PlayerCommandPacket 0x13
PlayerInputPacket 0x1B
PreLoginPacket 0xE8
ResourcePackPacket 0xE4
SetCarriedItemPacket 0xE5
SetCreativeModeSlotPacket 0x6B
SignUpdatePacket 0xE6
SwingPacket 0xE9
TeleportToEntityPacket 0xE7
UseItemOnPacket 0x89
UseItemPacket 0x0F
-->

## Serverbound
| Packet Name                | Packet ID | Notes |
|----------------------------|------|-------|
| InteractPacket             | 0x07 |       |
| MovePlayerPacket           | 0x0A |       |
| MovePlayerPacketPos        | 0x0B | ServerboundMovePlayerPacket::Pos      |
| MovePlayerPacketRot        | 0x0C | ServerboundMovePlayerPacket::Rot      |
| MovePlayerPacketPosRot     | 0x0D | ServerboundMovePlayerPacket::PosRot   |
| PlayerActionPacket         | 0x0E |       |
| UseItemPacket              | 0x0F |       |
| ContainerClickPacket       | 0x66 |       |
| SetCreativeModeSlotPacket  | 0x6B |       |
| ContainerButtonClickPacket | 0x6C |       |
| AcceptTeleportationPacket  | 0x87 |       |
| MoveVehiclePacket          | 0x88 |       |
| UseItemOnPacket            | 0x89 |       |
| PaddleBoatPacket           | 0x8A |       |
| ChatAutoCompletePacket     | 0xDD |       |
| ChatPacket                 | 0xDE |       |
| ContainerAckPacket         | 0xDF |       |
| ContainerClosePacket       | 0xE0 |       |
| CustomPayloadPacket        | 0xE1 |       |
| KeepAlivePacket            | 0xE2 |       |
| PlayerAbilitiesPacket      | 0xE3 |       |
| ResourcePackPacket         | 0xE4 |       |
| SetCarriedItemPacket       | 0xE5 |       |
| SignUpdatePacket           | 0xE6 |       |
| TeleportToEntityPacket     | 0xE7 |       |
| PreLoginPacket             | 0xE8 |       |
| SwingPacket                | 0xE9 |       |









