# 介绍

不知名退役老登的算法模板。最好成绩icpc区域赛银。

很多地方取自网络，并无主观抄袭意愿，仅作模板个人使用。若有侵权请联系我删除相关内容。

上传github方便我云端备份，同时开源给大家（？

# 环境配置
Obsidian

Pandoc，做导出word时使用并非刚需。

Obsidian第三方插件：Enhancing Export（导出word使用，非刚需）、Heading Shifter（编辑时快速更改标题编号，非刚需）、Local Images Plus（可以将复制的图片直接以MD5保存到本地，非刚需）。

# Enhancing Export 详细配置
选择模板：Word(.docx)

参数（需要更改文件路径）：--citeproc --csl "D:/notes/ty09/docxset/gb-t-7714-2015-numeric-bilingual-no-uppercase-no-url-doi.csl" --bibliography "D:/notes/ty09/docxset/ref.bib" -M reference-section-title="参考文献" -M link-citations=true --reference-doc="D:/notes/ty09/docxset/templates_refine.docx" -f markdown --resource-path="${currentDir}" --resource-path="${attachmentFolderPath}" -s -o "${outputPath}" -t docx

环境变量：HOME="${HOME}"
PATH="${HOME}\AppData\Local\Pandoc;${PATH}"
TEXINPUTS="${pluginDir}/textemplate/;"
