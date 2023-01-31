# 🔬 OpenMicroanatomy / QuPath Edu

OpenMicroanatomy is a free and open-source software to host & view whole slide images. It works in parallel with our QuPath extension called *QuPath Edu*, which adds new features to QuPath to make it more suitable as a learning / teaching tool, while still maintaining all the original features.


## Ecosystem

![Components](https://user-images.githubusercontent.com/45145923/215777288-06a4156d-eda9-42e3-999d-e41eff0aee31.png)

| Main repositories                                                                   | Description |
|------------------------------------------------------------------------------|-------------|
| [qupath-edu-extension](https://github.com/openmicroanatomy/qupath-extension) | A QuPath extension which communicates with the OpenMicroanatomy Server and adds new features such as enhanced annotations, slide tours, analyze remote slides and much more. |
| [openmicroanatomy-server](https://github.com/openmicroanatomy/server)        | Handles authentication, stores the QuPath projects for remote access, backups, converts slides into smaller tiles and such. |
| [openmicroanatomy-cloud](https://github.com/openmicroanatomy/web)            | A React Web App which communicates with the OpenMicroanatomy Server and provides a whole slide image viewer and other basic QuPath Edu features such as enhanced annotations, slide tours; it *does not* include any analysis features. |

