# Iris Gallery - Save to Secure Folder Morphe Patch

This repository contains the Morphe patch package (`.mpp`) for **Iris Gallery 0.70** enabling "Save to Secure Folder" on Samsung One UI devices without relying on Samsung Gallery.

## 📦 Files

- `iris-secure-folder-1.0.0.mpp` - The compiled Morphe Patch Package ready to import or upload to GitHub.
- `patches-bundle.json` - Bundle manifest file for Morphe App source import.
- `patches-list.json` - Metadata catalog of supported apps (`com.iris.gallery` v0.70).
- `src/main/kotlin/patches/SecureFolderHelper.kt` - Reverse-engineered Knox `SemPersonaManager` & `SemRemoteContentManager` implementation.
- `src/main/kotlin/patches/SecureFolderPatch.kt` - Morphe patch hook definition.

## 🚀 How to Upload to GitHub & Use in Morphe

1. **Create a GitHub Repository**:
   - Create a repository on GitHub (e.g. `https://github.com/USERNAME/iris-secure-folder-patch`).
   - Push this directory's files to your repository.

2. **Create a Release on GitHub**:
   - Go to Releases -> **Draft a new release**.
   - Set tag version to `v1.0.0`.
   - Upload `iris-secure-folder-1.0.0.mpp` as a release asset.

3. **Import into Morphe App**:
   - Open **Morphe App** on your Android device.
   - Go to **Settings** -> **Sources** / **Patch Sources**.
   - Add your repository URL (`https://github.com/USERNAME/iris-secure-folder-patch`) or select `iris-secure-folder-1.0.0.mpp` directly.
   - Select **Iris Gallery 0.70** and apply the **Save to Secure Folder** patch!
