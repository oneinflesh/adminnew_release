# Vethagama Nanban Office

Windows standalone admin desktop application. Download the ZIP from this repository's GitHub Releases page, extract the entire folder, and run `VethagamaNanbanOffice.exe`. Keep the EXE, `resources`, `locales`, and other extracted files together.

The built application is distributed as a Release asset, not as files in Git. The source project is in `admin_new` in the Vethagama Nanban workspace.

The local release folder contains both the unpacked desktop application and `VethagamaNanbanOffice.zip`. Upload the ZIP to GitHub Releases. From `admin_new`, `npm run release:standalone` rebuilds both into `adminnew_release`.
