## Reproducible Setup
To ensure everything runs smoothly and to avoid version conflicts, please use the following environment:

* **Unity Version:** `6000.1.17f1` [ (Download Here)](https://unity.com/releases/editor/whats-new/6000.1.17f1)
* **ML Agents:** `Release 23` [ (View Tag)](https://github.com/Unity-Technologies/ml-agents/releases/tag/release_23_tag)

## Dependency Chain
The following packages **must** be imported via the Unity Package Manager (UPM) in the specific order listed below before importing Overlord.

### 1. External Dependencies
| Order | Package Name | Git URL |
| :--- | :--- | :--- |
| 1 | **MyBox** | `https://github.com/Deadcows/mybox.git#1.8.0` |
| 2 | **Reorderable List** | `https://github.com/cfoulston/Unity-Reorderable-List.git#1.0.1` |
| 3 | **Dialogue Module** | `https://github.com/FellowshipOfTheGame/DialogueModule.git#upm` |

### 2. Main Package
Finally, import the Overlord package itself:
`https://github.com/varalta/Overlord-Tool.git`

> [!TIP]
> **How to install via Git:**
> In your Unity project, go to **Window** > **Package Manager**. Click the **+** icon in the top left, select **"Add package from git URL..."**, and paste the links above.

## Learning Resources
If you are new to Overlord, check out the official tutorial series recorded by Tyago Teoi to get up and running quickly.

* **[Overlord V1 Tutorial Playlist](https://www.youtube.com/playlist?list=PLPY-0In6XQ1s73zsz1Tcmu5T2hClxWTsR)**
