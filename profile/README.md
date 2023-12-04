# 🔬 OpenMicroanatomy / QuPath Edu

OpenMicroanatomy is a free and open-source software to host & view whole slide images. It works in parallel with our QuPath extension called *QuPath Edu*, which adds new features to QuPath to make it more suitable as a learning / teaching tool, while still maintaining all the original features.


## Ecosystem

![Components](https://github.com/openmicroanatomy/.github/assets/45145923/45113d84-914a-4ca6-ba59-dd310369f899)


| Main repositories                                                                   | Description |
|------------------------------------------------------------------------------|-------------|
| [qupath-edu-extension](https://github.com/openmicroanatomy/qupath-edu-extension) | A QuPath extension which communicates with the OpenMicroanatomy Server and adds new features such as enhanced annotations, slide tours, analyze remote slides and much more. |
| [server](https://github.com/openmicroanatomy/server) | Handles authentication, stores the QuPath projects for remote access, handles backups, converts slides into smaller tiles and much more. |
| [web](https://github.com/openmicroanatomy/web) | A React app which communicates with the OpenMicroanatomy Server and provides a whole slide image viewer and other basic QuPath Edu features such as enhanced annotations, slide tours; it *does not* include any analysis features. |

