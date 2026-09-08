# Third-Party Notices

Open MMORPG is released under the MIT License; see [LICENSE](LICENSE).

This file lists third-party components distributed with the kit, as required for
Unity Asset Store submissions. Each component below keeps the licence shipped in
its own folder.

## Components with a bundled licence

| Component | Licence | Copyright | Licence file |
| --- | --- | --- | --- |
| `Core` | MIT | 2026 Ittipon Teerapruettikulchai | [`Core/LICENSE`](Core/LICENSE) |
| `Database` | MIT | 2023 Ittipon Teerapruettikulchai | [`Database/LICENSE`](Database/LICENSE) |
| `MMO` | MIT | 2018 Ittipon Teerapruettikulchai | [`MMO/LICENSE`](MMO/LICENSE) |
| `Server` | MIT | 2023 Ittipon Teerapruettikulchai | [`Server/LICENSE`](Server/LICENSE) |
| `SharedData` | MIT | 2023 Ittipon Teerapruettikulchai | [`SharedData/LICENSE`](SharedData/LICENSE) |
| `ThirdParty/AddressableAssetTools` | MIT | 2024 Ittipon Teerapruettikulchai | [`ThirdParty/AddressableAssetTools/LICENSE`](ThirdParty/AddressableAssetTools/LICENSE) |
| `ThirdParty/AudioManager` | MIT | 2017 Ittipon Teerapruettikulchai | [`ThirdParty/AudioManager/LICENSE`](ThirdParty/AudioManager/LICENSE) |
| `ThirdParty/CameraAndInput` | MIT | 2017 Ittipon Teerapruettikulchai | [`ThirdParty/CameraAndInput/LICENSE`](ThirdParty/CameraAndInput/LICENSE) |
| `ThirdParty/DevExtension` | MIT | 2018 Ittipon Teerapruettikulchai | [`ThirdParty/DevExtension/LICENSE`](ThirdParty/DevExtension/LICENSE) |
| `ThirdParty/GraphicSettings` | MIT | 2021 Ittipon Teerapruettikulchai | [`ThirdParty/GraphicSettings/LICENSE`](ThirdParty/GraphicSettings/LICENSE) |
| `ThirdParty/LiteNetLibManager` | MIT | 2017 Ittipon Teerapruettikulchai | [`ThirdParty/LiteNetLibManager/LICENSE`](ThirdParty/LiteNetLibManager/LICENSE) |
| `ThirdParty/SerializableCallback` | MIT | 2017 Thor Brigsted | [`ThirdParty/SerializableCallback/LICENSE.md`](ThirdParty/SerializableCallback/LICENSE.md) |
| `ThirdParty/SerializationSurrogates` | MIT | 2018 Ittipon Teerapruettikulchai | [`ThirdParty/SerializationSurrogates/LICENSE`](ThirdParty/SerializationSurrogates/LICENSE) |
| `ThirdParty/SpatialPartitioningSystems` | MIT | 2025 Ittipon Teerapruettikulchai | [`ThirdParty/SpatialPartitioningSystems/LICENSE`](ThirdParty/SpatialPartitioningSystems/LICENSE) |
| `ThirdParty/UnityEditorUtils` | MIT | 2018 Ittipon Teerapruettikulchai | [`ThirdParty/UnityEditorUtils/LICENSE`](ThirdParty/UnityEditorUtils/LICENSE) |
| `ThirdParty/UnityRestClient` | MIT | 2021 Ittipon Teerapruettikulchai | [`ThirdParty/UnityRestClient/LICENSE`](ThirdParty/UnityRestClient/LICENSE) |
| `ThirdParty/UpdateManager` | MIT | 2026 Ittipon Teerapruettikulchai | [`ThirdParty/UpdateManager/LICENSE`](ThirdParty/UpdateManager/LICENSE) |
| `ThirdParty/xNode` | MIT | 2017 Thor Brigsted | [`ThirdParty/xNode/LICENSE.md`](ThirdParty/xNode/LICENSE.md) |

## Components that still need a licence recorded

These ship with the kit but carry no licence file in this repository. Each one
must be confirmed, and its licence text added, before an Asset Store submission.

| Component | Path | Notes |
| --- | --- | --- |
| Colored Hierarchy Headers | `ThirdParty/ColoredHierarchyHeaders` | Authored by Dands Salaun per its `package.json`, which declares no licence. |
| LiteNetLib | `ThirdParty/LiteNetLibManager/Plugins/LiteNetLib` | Source headers state the MIT licence; the licence file itself is not bundled. |
| UniTask | `ThirdParty/LiteNetLibManager/Plugins/UniTask` | Vendored source with no licence file bundled. |
| ZString | `ThirdParty/LiteNetLibManager/Plugins/ZString` | Source headers state the MIT licence; the licence file itself is not bundled. |

### Compiled libraries

Binaries are shipped without accompanying licence text. Confirm each one, and note
that Asset Store guideline 1.5.a restricts executables, so the native SQLite
libraries in particular are worth checking with review.

| Library | Path |
| --- | --- |
| `ConcurrentCollections.dll` | `Core/Plugins/ConcurrentCollections.dll` |
| `I18N.West.dll` | `MMO/Plugins/I18N.West.dll` |
| `I18N.dll` | `MMO/Plugins/I18N.dll` |
| `Mono.Data.Sqlite.dll` | `MMO/Plugins/Mono.Data.Sqlite.dll` |
| `MySqlConnector.dll` | `MMO/Plugins/MySqlConnector.dll` |
| `sqlite3.dll` | `MMO/Plugins/SQLite_x64/sqlite3.dll` |
| `sqlite3.dll` | `MMO/Plugins/SQLite_x86/sqlite3.dll` |
| `System.Diagnostics.DiagnosticSource.dll` | `MMO/Plugins/System.Diagnostics.DiagnosticSource.dll` |
| `Fleck.dll` | `ThirdParty/LiteNetLibManager/Plugins/Fleck.dll` |
| `System.Runtime.CompilerServices.Unsafe.dll` | `ThirdParty/LiteNetLibManager/Plugins/System.Runtime.CompilerServices.Unsafe.dll` |
| `SerializeRegistrySourceGenerator.dll` | `ThirdParty/LiteNetLibManager/Scripts/SourceGenerators/SerializeRegistrySourceGenerator.dll` |
