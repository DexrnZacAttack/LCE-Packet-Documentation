> [!NOTE]  
> Estimated Size "Variable" means calculations in the code are done to figure out the estimated size.
> Additionally, if there is no Estimated Size for a packet, it means the function was missing for that packet.

## Clientbound
<!-- These need sorting. -->
| Packet Name                        | Packet ID  | Internal ID | Estimated Size | Notes                              |
| ---------------------------------- | ---------- | ----------- | -------------- | ---------------------------------- |
| KeepAlivePacket                    | 0x00       |             | 0x04           |                                    |
| LoginPacket                        | 0x01       |             | Variable       |                                    |
| PreLoginPacket                     | 0x02       |             | Variable       |                                    |
| ChatPacket                         | 0x03       |             |                |                                    |
| SetTimePacket                      | 0x04       |             | 0x10           |                                    |
| SetEquippedItemPacket              | 0x05       |             | 0x08           |                                    |
| SetSpawnPositionPacket             | 0x06       |             | 0x0C           |                                    |
| SetHealthPacket                    | 0x08       |             | 0x10           |                                    |
| RespawnPacket                      | 0x09       |             | Variable       |                                    |
| SetCarriedItemPacket               | 0x10       |             | 0x02           |                                    |
| PlayerSleepPacket                  | 0x11       |             |                |                                    |
| AnimatePacket                      | 0x12       |             | 0x05           |                                    |
| AddPlayerPacket                    | 0x14       |             | Variable       |                                    |
| TakeItemEntityPacket               | 0x16       |             | 0x08           |                                    |
| AddEntityPacket                    | 0x17       |             | Variable       |                                    |
| AddMobPacket                       | 0x18       |             | Variable       |                                    |
| AddPaintingPacket                  | 0x19       |             | Variable       |                                    |
| AddExperienceOrbPacket             | 0x1A       |             | 0x12           |                                    |
| SetEntityMotionPacket              | 0x1C       |             | Variable       |                                    |
| RemoveEntitiesPacket               | 0x1D       |             | Variable       |                                    |
| MoveEntityPacket                   | 0x1E       |             | 0x02           |                                    |
| MoveEntityPacketPos                | 0x1F       |             | 0x05           | ClientboundMoveEntityPacket::Pos   |
| MoveEntityPacketRot                | 0x20       |             | 0x04           | ClientboundMoveEntityPacket::Rot   |
| MoveEntityPacketPosRot             | 0x21       |             | 0x07           | ClientboundMoveEntityPacket::PosRot|
| TeleportEntityPacket               | 0x22       |             | 0x0A           |                                    |
| RotateHeadPacket                   | 0x23       |             | 0x05           |                                    |
| EntityEventPacket                  | 0x26       |             | 0x09           |                                    |
| SetEntityLinkPacket                | 0x27       |             | 0x08           |                                    |
| SetEntityDataPacket                | 0x28       |             | 0x05           |                                    |
| UpdateAttributesPacket             | 0x2C       |             | Variable       |                                    |
| SetExperiencePacket                | 0x2B       |             | 0x08           |                                    |
| RemoveMobEffectPacket              | 0x2A       |             | 0x05           |                                    |
| UpdateMobEffectPacket              | 0x29       |             | 0x08           |                                    |
| PowerupPacket                      | 0xAB       |             | 0x02           |                                    |
| BossEventPacket                    | 0x8B       |             | Variable       |                                    |
| MoveVehiclePacket                  | 0x85       |             |                |                                    |
| BlockEntityDataPacket              | 0x84       |             | 0x19           |                                    |
| SoundPacket                        | 0x3E       |             | 0x18           |                                    |
| ExplodePacket                      | 0x3C       |             | Variable       |                                    |
| LevelEventPacket                   | 0x3D       |             | 0x15           |                                    |
| LevelParticlesPacket               | 0x3F       |             | 0x40           |                                    |
| BlockUpdatePacket                  | 0x35       |             | 0x08           |                                    |
| BlockEventPacket                   | 0x36       |             | 0x0E           |                                    |
| BlockDestructionPacket             | 0x37       |             | 0x0D           |                                    |
| ChunkBlocksUpdatePacket            | 0x34       |             | Variable       |                                    |
| AddGlobalEntityPacket              | 0x47       |             | 0x11           |                                    |
| GameEventPacket                    | 0x46       |             | 0x03           |                                    |
| ContainerOpenPacket                | 0x64       |             | Variable       |                                    |
| ContainerClosePacket               | 0x65       |             | 0x01           |                                    |
| ContainerSetSlotPacket             | 0x67       |             | 0x08           |                                    |
| ContainerSetDataPacket             | 0x69       |             | 0x05           |                                    |
| ContainerSetContentPacket          | 0x68       |             | Variable       |                                    |
| ContainerAckPacket                 | 0x6A       |             | 0x04           |                                    |
| SetPassengersPacket                | 0x86       |             |                |                                    |
| AwardStatPacket                    | 0xC8       |             | 0x06           |                                    |
| PlayerAbilitiesPacket              | 0xCA       |             |                |                                    |
| MapItemDataPacket                  | 0xD3       |             |                |                                    |
| OpenSignEditorPacket               | 0xD4       |             |                |                                    |
| PlayerCombatPacket                 | 0xD5       |             |                |                                    |
| PlayerPositionPacket               | 0xD6       |             |                |                                    |
| SetPlayerTeamPacket                | 0xD1       |             | Variable       |                                    |
| ResourcePackPacket                 | 0xD8       |             |                |                                    |
| SetTitlesPacket                    | 0xDB       |             |                |                                    |
| TabListPacket                      | 0xDC       |             |                |                                    |
| CooldownPacket                     | 0xEC       |             |                |                                    |
| MGPlayerSettingsUpdatePacket       | 0xEF       |             | 0x68           |                                    |
| BlockCollectionDestructionPacket   | 0xEB       |             | Variable       |                                    |
| DamageIndicatorPacket              | 0xEA       |             | 0x09           |                                    |
| CustomPayloadPacket                | 0xFA       |             | Variable       |                                    |
| ChangeDifficultyPacket             | 0xFD       |             |                |                                    |

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
| Packet Name                | Packet ID | Internal ID | Estimated Size | Notes                                      |
|----------------------------|-----------|-------------|----------------|--------------------------------------------|
| InteractPacket             | 0x07      |             |                |                                            |
| MovePlayerPacket           | 0x0A      |             |                |                                            |
| MovePlayerPacketPos        | 0x0B      |             |                | ServerboundMovePlayerPacket::Pos           |
| MovePlayerPacketRot        | 0x0C      |             |                | ServerboundMovePlayerPacket::Rot           |
| MovePlayerPacketPosRot     | 0x0D      |             |                | ServerboundMovePlayerPacket::PosRot        |
| PlayerActionPacket         | 0x0E      |             |                |                                            |
| UseItemPacket              | 0x0F      |             |                |                                            |
| ContainerClickPacket       | 0x66      |             |                |                                            |
| SetCreativeModeSlotPacket  | 0x6B      |             |                |                                            |
| ContainerButtonClickPacket | 0x6C      |             |                |                                            |
| AcceptTeleportationPacket  | 0x87      |             |                |                                            |
| MoveVehiclePacket          | 0x88      |             |                |                                            |
| UseItemOnPacket            | 0x89      |             |                |                                            |
| PaddleBoatPacket           | 0x8A      |             |                |                                            |
| ChatAutoCompletePacket     | 0xDD      |             |                |                                            |
| ChatPacket                 | 0xDE      |             |                |                                            |
| ContainerAckPacket         | 0xDF      |             |                |                                            |
| ContainerClosePacket       | 0xE0      |             |                |                                            |
| CustomPayloadPacket        | 0xE1      |             |                |                                            |
| KeepAlivePacket            | 0xE2      |             |                |                                            |
| PlayerAbilitiesPacket      | 0xE3      |             |                |                                            |
| ResourcePackPacket         | 0xE4      |             |                |                                            |
| SetCarriedItemPacket       | 0xE5      |             |                |                                            |
| SignUpdatePacket           | 0xE6      |             |                |                                            |
| TeleportToEntityPacket     | 0xE7      |             |                |                                            |
| PreLoginPacket             | 0xE8      |             |                |                                            |
| SwingPacket                | 0xE9      |             |                |                                            |

<!--
for packets that don't start with either Clientbound or Serverbound
-->
## Other (Both ways maybe?)
| Packet Name                    | Packet ID | Internal ID | Estimated Size | Notes                                      |
|--------------------------------|-----------|-------------|----------------|--------------------------------------------|
| ChunkVisibilityPacket          | 0x32      |             | 0x04           |                                            |
| BlockRegionUpdatePacket        | 0x33      |             |                |                                            |
| CraftItemPacket                | 0x96      |             |                |                                            |
| TradeItemPacket                | 0x97      |             |                |                                            |
| DebugOptionsPacket             | 0x98      |             |                |                                            |
| ServerSettingsChangedPacket    | 0x99      |             |                |                                            |
| TexturePacket                  | 0x9A      |             |                |                                            |
| ChunkVisibilityAreaPacket      | 0x9B      |             | 0x08           |                                            |
| UpdateProgressPacket           | 0x9C      |             |                |                                            |
| TextureChangePacket            | 0x9D      |             |                |                                            |
| UpdateGameRuleProgressPacket   | 0x9E      |             |                |                                            |
| KickPlayerPacket               | 0x9F      |             |                |                                            |
| PlayerInfoPacket               | 0xC9      |             |                |                                            |
| GameCommandPacket              | 0xA7      |             |                |                                            |
| MapSelectInfoPacket            | 0xA8      |             |                |                                            |
| VotePacket                     | 0xA9      |             |                |                                            |
| TextureAndGeometryPacket       | 0xA0      |             |                |                                            |
| TextureAndGeometryChangePacket | 0xA1      |             |                |                                            |
| MoveEntityPacketSmall          | 0xA2      |             |                |                                            |
| MoveEntityPacketSmallPos       | 0xA3      |             |                | MoveEntityPacketSmall::Pos                 |
| MoveEntityPacketSmallRot       | 0xA4      |             |                | MoveEntityPacketSmall::Rot                 |
| MoveEntityPacketSmallPosRot    | 0xA5      |             |                | MoveEntityPacketSmall::PosRot              |
| XZPacket                       | 0xA6      |             |                |                                            |
| GameModePacket                 | 0xD2      |             |                |                                            |
| GetInfoPacket                  | 0xFE      |             |                |                                            |
| DisconnectPacket               | 0xFF      |             |                |                                            |











