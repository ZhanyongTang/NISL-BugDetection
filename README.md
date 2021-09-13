# NISL Bug Detection Tool

This is the information of vulnerabilities founded by NISL bug detection tool.

**March 2021** - The repository opened by NISL Security Group.

## Vulnerabilities List


|NO. |     Project     |  Version |          Issue link           |            Poc           |   Contributor   |    Supervisor    |    IssueState    |   CVEState   |   Date   |
| :----: | :-------------: | :--------: |:-----------------------------: | :----------------------: | :------: | :--------: | :------------: | :------------: |:-------:|
|1| ok-file-formats  | 01be744 |[heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/11) | [heap-buffer-overflow-1](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-1/heap-buffer-overflow-1.jpg)  |  xxrz   |  zytang  |  Ensure  |  -  | 05/03/2021  |
|2| ok-file-formats | 97f78ca | [heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/12) | [heap-buffer-overflow-2](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-2/heap-buffer-overflow-2.jpg)  |  wjl / xxrz   |  zytang  |   Ensure  | -  | 26/03/2021  |
|☆3| OpenEXR  | 2.2.0 | [allocation-size-too-big](https://github.com/AcademySoftwareFoundation/openexr/issues/996) | [allocation-size-too-big](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/OpenEXR/allocation-size-too-big/allocation-size-too-big)  |  wjl / xxrz   |  zytang  |  Ensure  | CVE-2017-14988  | 02/04/2021  |
|★4| ImageMagick      | [7.0.11-5](https://github.com/ImageMagick/ImageMagick/tree/7.0.11-5) | [memory_leaks](https://github.com/ImageMagick/ImageMagick/issues/3540) | [memory_leaks](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ImageMagick/memory_leaks/memory_leaks)  |  wjl / xxrz   |  zytang  |  Ensure  | CVE-2021-3574 |  13/04/2021  |
|5| ok-file-formats      | [203defd](https://github.com/brackeen/ok-file-formats/commit/203defdfb2c8b1207a392493a09145c1b54bb070) | [heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/15) | [heap-buffer-overflow-3](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-3/heap-buffer-overflow-3.png)  |  zyk / xxrz   |  zytang  |  Ensure  | - |  07/06/2021  |
|6| ok-file-formats      | [203defd](https://github.com/brackeen/ok-file-formats/commit/203defdfb2c8b1207a392493a09145c1b54bb070) | [heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/16) | [heap-buffer-overflow-4](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-4/heap-buffer-overflow-4.png)  |  zyk / xxrz   |  zytang  |  Ensure  | - |  07/06/2021  |
|7| ok-file-formats      | [203defd](https://github.com/brackeen/ok-file-formats/commit/203defdfb2c8b1207a392493a09145c1b54bb070) | [heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/17) | [heap-buffer-overflow-5](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-5/heap-buffer-overflow-5.png)  |  zyk / xxrz   |  zytang  |  Ensure  | - |  07/06/2021  |
|8| ok-file-formats      | [203defd](https://github.com/brackeen/ok-file-formats/commit/203defdfb2c8b1207a392493a09145c1b54bb070) | [heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/18) | [heap-buffer-overflow-6](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-6/heap-buffer-overflow-6.png)  |  zyk / xxrz   |  zytang  |  Ensure  | - |  07/06/2021  |
|9| ok-file-formats      | [203defd](https://github.com/brackeen/ok-file-formats/commit/203defdfb2c8b1207a392493a09145c1b54bb070) | [heap-buffer-overflow](https://github.com/brackeen/ok-file-formats/issues/19) | [heap-buffer-overflow-7](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/ok-file-formats/heap-buffer-overflow-7/heap-buffer-overflow-7.png)  |  zyk / xxrz   |  zytang  |  Ensure  | - |  07/06/2021  |
|☆10| openjpeg      | [a44547d](https://github.com/google/oss-fuzz/commit/a44547d8d6f78ad7ce02323ecc33382a1d628e39) | [heap-buffer-overflow](https://github.com/uclouvain/openjpeg/issues/1363) | [heap-buffer-overflow-1](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/openjpeg/heap-buffer-overflow/heap-buffer-overflow-1)  |  xxrz   |  zytang  |  Ensure  | - |  10/06/2021  |
|11| packJPG      | [v2.5k](https://github.com/packjpg/packJPG/tree/2.5k) | [memory_leaks](https://github.com/packjpg/packJPG/issues/29) | [memory_leaks](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/packJPG/memory%20leaks/memory_leaks)  |  zlc / wjl / xxrz   |  zytang  |  Waiting  | - |  11/08/2021  |
|12| packJPG      | [v2.5k](https://github.com/packjpg/packJPG/tree/2.5k) | [global-buffer-overflow](https://github.com/packjpg/packJPG/issues/30) | [global-buffer-overflow](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/packJPG/global-buffer-overfllow/global%20buffer%20overflow.zip)  |  zlc / wjl / xxrz  |  zytang  |  Waiting  | - |  13/08/2021  |
|13| mediancut-posterizer      | [2.1](https://github.com/kornelski/mediancut-posterizer/tree/2.1) | [SEGV](https://github.com/kornelski/mediancut-posterizer/issues/15) | [SEGV](https://github.com/NISL-SecurityGroup/NISL-BugDetection/blob/main/project/mediancut-posterizer/SEGV/SEGV.png)  |  zyk / wjl / xxrz  |  zytang  |  Waiting  | - |  14/08/2021  |


> Note:
> 
> ★ We have applied for a CVE ID for this bug.
> 
> ☆ This bug already has a CVE ID when we detect it.




## Contact
Rongze Xu - xxurongze@gmail.com

Jialing Wu - 2017118025@stumail.nwu.edu.cn

Huanting Wang - wanghuanting@stumail.nwu.edu.cn

Zhanyong Tang - zytang@nwu.edu.cn
