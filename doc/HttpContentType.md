# HTTP Content-type 对照表

* [HTTP Content-type 对照表](http://tools.jb51.net/table/http_content_type)

* Content-Type，内容类型，一般是指网页中存在的Content-Type，用于定义网络文件的类型和网页的编码，决定浏览器将以什么形式、什么编码读取这个文件，比如用PHP输出图片文件、JSON数据、XML文件等非HTML内容时，就必须用header函数来指定Content-Type，才能达到输出一张图片或是其它指定内容类型的需求。

#### Application Type

| 文件扩展名 | Content-Type(Mime-Type)                 | 描述                                                         |
| :--------- | :-------------------------------------- | :----------------------------------------------------------- |
| .          | application/x-                          |                                                              |
| .*         | application/octet-stream                | 二进制流，不知道下载文件类型                                 |
| .pdf       | application/pdf                         | PDF（Portable Document Format的简称，意为“便携式文件格式”）  |
| .ai        | application/postscript                  | PostScript（PS）是主要用于电子产业和桌面出版领域的一种页面描述语言和编程语言。 |
| .xml       | application/atom+xml                    | Atom feeds                                                   |
| .js        | application/ecmascript                  | 相当于application/javascript但是严格的处理规则               |
| .edi       | application/EDI-X12                     | EDI ANSI ASC X12数据                                         |
| .edi       | application/EDIFACT                     | EDI EDIFACT数据                                              |
| .json      | application/json                        | JSON（JavaScript Object Notation）                           |
| .js        | application/javascript                  | ECMAScript/JavaScript（相当于application/ecmascript但是宽松的处理规则） |
| .ogg       | application/ogg                         | Ogg, 视频文件格式                                            |
| .rdf       | application/rdf+xml                     | 资源描述框架（Resource Description Framework，缩写 RDF），是万维网联盟（W3C）提出的一组标记语言的技术标准，以便更为丰富地描述和表达网络资源的内容与结构。 |
| .xml       | application/rss+xml                     | RSS（Really Simple Syndication,简易信息聚合）是一种消息来源格式规范，用以聚合经常发布更新数据的网站，例如博客文章、新闻、音频或视频的网摘 |
| .xml       | application/soap+xml                    | 简单对象访问协议（SOAP，全写为Simple Object Access Protocol）是交换数据的一种协议规范，使用在计算机网络Web服务（web service）中，交换带结构信息。 |
| .woff      | application/font-woff                   | Web开放字体格式（Web Open Font Format，简称WOFF）是一种网页所采用的字体格式标准。（推荐使用；使用application/x-font-woff直到它变为官方标准） |
| .xhtml     | application/xhtml+xml                   | 可扩展超文本标记语言（eXtensible HyperText Markup Language，XHTML），是一种标记语言，表现方式与超文本标记语言（HTML）类似，不过语法上更加严格。 |
| .xml       | application/xml                         | 可扩展标记语言（英语：eXtensible Markup Language，简称: XML），是一种标记语言。 |
| .dtd       | application/xml-dtd                     | XML文件的文件型别定义（Document Type Definition）可以看成一个或者多个XML文件的模板，在这里可以定义XML文件中的元素、元素的属性、元素的排列方式、元素包含的内容等等。 |
| .xml       | application/xop+xml                     | 二进制优化封装协议(Xmlbinary Optimized Packaging)            |
| .zip       | application/zip                         | ZIP压缩文件                                                  |
| .gzip      | application/gzip                        | Gzip是若干种文件压缩程序的简称，通常指GNU计划的实现，此处的gzip代表GNU zip。 |
| .xls       | application/x-xls                       | XLS 就是 Microsoft Excel 工作表，是一种非常常用的电子表格格式。 |
| .001       | application/x-001                       |                                                              |
| .301       | application/x-301                       |                                                              |
| .906       | application/x-906                       |                                                              |
| .a11       | application/x-a11                       |                                                              |
| .awf       | application/vnd.adobe.workflow          |                                                              |
| .bmp       | application/x-bmp                       |                                                              |
| .c4t       | application/x-c4t                       |                                                              |
| .cal       | application/x-cals                      |                                                              |
| .cdf       | application/x-netcdf                    |                                                              |
| .cel       | application/x-cel                       |                                                              |
| .cg4       | application/x-g4                        |                                                              |
| .cit       | application/x-cit                       |                                                              |
| .bot       | application/x-bot                       |                                                              |
| .c90       | application/x-c90                       |                                                              |
| .cat       | application/vnd.ms-pki.seccat           |                                                              |
| .cdr       | application/x-cdr                       |                                                              |
| .cer       | application/x-x509-ca-cert              |                                                              |
| .cgm       | application/x-cgm                       |                                                              |
| .cmx       | application/x-cmx                       |                                                              |
| .crl       | application/pkix-crl                    |                                                              |
| .csi       | application/x-csi                       |                                                              |
| .cut       | application/x-cut                       |                                                              |
| .dbm       | application/x-dbm                       |                                                              |
| .cmp       | application/x-cmp                       |                                                              |
| .cot       | application/x-cot                       |                                                              |
| .crt       | application/x-x509-ca-cert              |                                                              |
| .dbf       | application/x-dbf                       |                                                              |
| .dbx       | application/x-dbx                       |                                                              |
| .dcx       | application/x-dcx                       |                                                              |
| .dgn       | application/x-dgn                       |                                                              |
| .dll       | application/x-msdownload                |                                                              |
| .dot       | application/msword                      |                                                              |
| .der       | application/x-x509-ca-cert              |                                                              |
| .dib       | application/x-dib                       |                                                              |
| .doc       | application/msword                      |                                                              |
| .drw       | application/x-drw                       |                                                              |
| .dwf       | application/x-dwf                       |                                                              |
| .dxb       | application/x-dxb                       |                                                              |
| .edn       | application/vnd.adobe.edn               |                                                              |
| .dwg       | application/x-dwg                       |                                                              |
| .dxf       | application/x-dxf                       |                                                              |
| .emf       | application/x-emf                       |                                                              |
| .epi       | application/x-epi                       |                                                              |
| .eps       | application/postscript                  |                                                              |
| .exe       | application/x-msdownload                |                                                              |
| .fdf       | application/vnd.fdf                     |                                                              |
| .eps       | application/x-ps                        |                                                              |
| .etd       | application/x-ebx                       |                                                              |
| .fif       | application/fractals                    |                                                              |
| .frm       | application/x-frm                       |                                                              |
| .gbr       | application/x-gbr                       |                                                              |
| .g4        | application/x-g4                        |                                                              |
| .gl2       | application/x-gl2                       |                                                              |
| .hgl       | application/x-hgl                       |                                                              |
| .hpg       | application/x-hpgl                      |                                                              |
| .hqx       | application/mac-binhex40                |                                                              |
| .hta       | application/hta                         |                                                              |
| .gp4       | application/x-gp4                       |                                                              |
| .hmr       | application/x-hmr                       |                                                              |
| .hpl       | application/x-hpl                       |                                                              |
| .hrf       | application/x-hrf                       |                                                              |
| .icb       | application/x-icb                       |                                                              |
| .ico       | application/x-ico                       |                                                              |
| .ig4       | application/x-g4                        |                                                              |
| .iii       | application/x-iphone                    |                                                              |
| .ins       | application/x-internet-signup           |                                                              |
| .iff       | application/x-iff                       |                                                              |
| .igs       | application/x-igs                       |                                                              |
| .img       | application/x-img                       |                                                              |
| .isp       | application/x-internet-signup           |                                                              |
| .jpe       | application/x-jpe                       |                                                              |
| .js        | application/x-javascript                |                                                              |
| .jpg       | application/x-jpg                       |                                                              |
| .lar       | application/x-laplayer-reg              |                                                              |
| .latex     | application/x-latex                     |                                                              |
| .lbm       | application/x-lbm                       |                                                              |
| .ls        | application/x-javascript                |                                                              |
| .ltr       | application/x-ltr                       |                                                              |
| .man       | application/x-troff-man                 |                                                              |
| .mdb       | application/msaccess                    |                                                              |
| .mac       | application/x-mac                       |                                                              |
| .mdb       | application/x-mdb                       |                                                              |
| .mfp       | application/x-shockwave-flash           |                                                              |
| .mi        | application/x-mi                        |                                                              |
| .mil       | application/x-mil                       |                                                              |
| .mocha     | application/x-javascript                |                                                              |
| .mpd       | application/vnd.ms-project              |                                                              |
| .mpp       | application/vnd.ms-project              |                                                              |
| .mpt       | application/vnd.ms-project              |                                                              |
| .mpw       | application/vnd.ms-project              |                                                              |
| .mpx       | application/vnd.ms-project              |                                                              |
| .mxp       | application/x-mmxp                      |                                                              |
| .nrf       | application/x-nrf                       |                                                              |
| .out       | application/x-out                       |                                                              |
| .p12       | application/x-pkcs12                    |                                                              |
| .p7c       | application/pkcs7-mime                  |                                                              |
| .p7r       | application/x-pkcs7-certreqresp         |                                                              |
| .pc5       | application/x-pc5                       |                                                              |
| .pcl       | application/x-pcl                       |                                                              |
| .pdx       | application/vnd.adobe.pdx               |                                                              |
| .pgl       | application/x-pgl                       |                                                              |
| .pko       | application/vnd.ms-pki.pko              |                                                              |
| .p10       | application/pkcs10                      |                                                              |
| .p7b       | application/x-pkcs7-certificates        |                                                              |
| .p7m       | application/pkcs7-mime                  |                                                              |
| .p7s       | application/pkcs7-signature             |                                                              |
| .pci       | application/x-pci                       |                                                              |
| .pcx       | application/x-pcx                       |                                                              |
| .pdf       | application/pdf                         |                                                              |
| .pfx       | application/x-pkcs12                    |                                                              |
| .pic       | application/x-pic                       |                                                              |
| .pl        | application/x-perl                      |                                                              |
| .plt       | application/x-plt                       |                                                              |
| .png       | application/x-png                       |                                                              |
| .ppa       | application/vnd.ms-powerpoint           |                                                              |
| .pps       | application/vnd.ms-powerpoint           |                                                              |
| .ppt       | application/x-ppt                       |                                                              |
| .prf       | application/pics-rules                  |                                                              |
| .prt       | application/x-prt                       |                                                              |
| .ps        | application/postscript                  |                                                              |
| .pwz       | application/vnd.ms-powerpoint           |                                                              |
| .ra        | audio/vnd.rn-realaudio                  | RealAudio是一种由RealNetworks发展的RealMedia多媒体音频文件格式，仅指RealPlayer中能够识别的音频文件，也可以理解为real格式的音频文件。 |
| .ras       | application/x-ras                       |                                                              |
| .pot       | application/vnd.ms-powerpoint           |                                                              |
| .ppm       | application/x-ppm                       |                                                              |
| .ppt       | application/vnd.ms-powerpoint           |                                                              |
| .pr        | application/x-pr                        |                                                              |
| .prn       | application/x-prn                       |                                                              |
| .ps        | application/x-ps                        |                                                              |
| .ptn       | application/x-ptn                       |                                                              |
| .red       | application/x-red                       |                                                              |
| .rjs       | application/vnd.rn-realsystem-rjs       |                                                              |
| .rlc       | application/x-rlc                       |                                                              |
| .rm        | application/vnd.rn-realmedia            |                                                              |
| .rat       | application/rat-file                    |                                                              |
| .rec       | application/vnd.rn-recording            |                                                              |
| .rgb       | application/x-rgb                       |                                                              |
| .rjt       | application/vnd.rn-realsystem-rjt       |                                                              |
| .rle       | application/x-rle                       |                                                              |
| .rmf       | application/vnd.adobe.rmf               |                                                              |
| .rmj       | application/vnd.rn-realsystem-rmj       |                                                              |
| .rmp       | application/vnd.rn-rn_music_package     |                                                              |
| .rmvb      | application/vnd.rn-realmedia-vbr        |                                                              |
| .rnx       | application/vnd.rn-realplayer           |                                                              |
| .rpm       | audio/x-pn-realaudio-plugin             |                                                              |
| .rms       | application/vnd.rn-realmedia-secure     |                                                              |
| .rmx       | application/vnd.rn-realsystem-rmx       |                                                              |
| .rsml      | application/vnd.rn-rsml                 |                                                              |
| .rtf       | application/msword                      |                                                              |
| .rv        | video/vnd.rn-realvideo                  |                                                              |
| .sat       | application/x-sat                       |                                                              |
| .sdw       | application/x-sdw                       |                                                              |
| .slb       | application/x-slb                       |                                                              |
| .rtf       | application/x-rtf                       |                                                              |
| .sam       | application/x-sam                       |                                                              |
| .sdp       | application/sdp                         |                                                              |
| .sit       | application/x-stuffit                   |                                                              |
| .sld       | application/x-sld                       |                                                              |
| .smi       | application/smil                        |                                                              |
| .smk       | application/x-smk                       |                                                              |
| .smil      | application/smil                        |                                                              |
| .spc       | application/x-pkcs7-certificates        |                                                              |
| .spl       | application/futuresplash                |                                                              |
| .ssm       | application/streamingmedia              |                                                              |
| .stl       | application/vnd.ms-pki.stl              |                                                              |
| .sst       | application/vnd.ms-pki.certstore        |                                                              |
| .tdf       | application/x-tdf                       |                                                              |
| .tga       | application/x-tga                       |                                                              |
| .sty       | application/x-sty                       |                                                              |
| .swf       | application/x-shockwave-flash           |                                                              |
| .tg4       | application/x-tg4                       |                                                              |
| .tif       | application/x-tif                       |                                                              |
| .vdx       | application/vnd.visio                   |                                                              |
| .vpg       | application/x-vpeg005                   |                                                              |
| .vsd       | application/x-vsd                       |                                                              |
| .vst       | application/vnd.visio                   |                                                              |
| .vsw       | application/vnd.visio                   |                                                              |
| .vtx       | application/vnd.visio                   |                                                              |
| .torrent   | application/x-bittorrent                |                                                              |
| .vda       | application/x-vda                       |                                                              |
| .vsd       | application/vnd.visio                   |                                                              |
| .vss       | application/vnd.visio                   |                                                              |
| .vst       | application/x-vst                       |                                                              |
| .vsx       | application/vnd.visio                   |                                                              |
| .wb1       | application/x-wb1                       |                                                              |
| .wb3       | application/x-wb3                       |                                                              |
| .wiz       | application/msword                      |                                                              |
| .wk4       | application/x-wk4                       |                                                              |
| .wks       | application/x-wks                       |                                                              |
| .wb2       | application/x-wb2                       |                                                              |
| .wk3       | application/x-wk3                       |                                                              |
| .wkq       | application/x-wkq                       |                                                              |
| .wmf       | application/x-wmf                       |                                                              |
| .wmd       | application/x-ms-wmd                    |                                                              |
| .wp6       | application/x-wp6                       |                                                              |
| .wpg       | application/x-wpg                       |                                                              |
| .wq1       | application/x-wq1                       |                                                              |
| .wri       | application/x-wri                       |                                                              |
| .ws        | application/x-ws                        |                                                              |
| .wmz       | application/x-ms-wmz                    |                                                              |
| .wpd       | application/x-wpd                       |                                                              |
| .wpl       | application/vnd.ms-wpl                  |                                                              |
| .wr1       | application/x-wr1                       |                                                              |
| .wrk       | application/x-wrk                       |                                                              |
| .ws2       | application/x-ws                        |                                                              |
| .xdp       | application/vnd.adobe.xdp               |                                                              |
| .xfd       | application/vnd.adobe.xfd               |                                                              |
| .xfdf      | application/vnd.adobe.xfdf              |                                                              |
| .xls       | application/vnd.ms-excel                |                                                              |
| .xwd       | application/x-xwd                       |                                                              |
| .sis       | application/vnd.symbian.install         |                                                              |
| .x_t       | application/x-x_t                       |                                                              |
| .apk       | application/vnd.android.package-archive |                                                              |
| .x_b       | application/x-x_b                       |                                                              |
| .sisx      | application/vnd.symbian.install         |                                                              |
| .ipa       | application/vnd.iphone                  |                                                              |
| .xap       | application/x-silverlight-app           |                                                              |
| .xlw       | application/x-xlw                       |                                                              |
| .xpl       | audio/scpls                             |                                                              |
| .anv       | application/x-anv                       |                                                              |
| .uin       | application/x-icq                       |                                                              |

#### Text Type

| 文件扩展名 | Content-Type(Mime-Type) | 描述                                                         |
| :--------- | :---------------------- | :----------------------------------------------------------- |
| .323       | text/h323               |                                                              |
| .biz       | text/xml                |                                                              |
| .cml       | text/xml                |                                                              |
| .asa       | text/asa                |                                                              |
| .asp       | text/asp                |                                                              |
| .css       | text/css                | 层叠样式表（英语：Cascading Style Sheets，简写CSS），又称串样式列表、层次结构式样式表文件，一种用来为结构化文档（如HTML文档或XML应用）添加样式（字体、间距和颜色等）的计算机语言，由W3C定义和维护。 |
| .csv       | text/csv                | 逗号分隔值（Comma-Separated Values，CSV，有时也称为字符分隔值，因为分隔字符也可以不是逗号），其文件以纯文本形式存储表格数据（数字和文本）。 |
| .dcd       | text/xml                |                                                              |
| .dtd       | text/xml                |                                                              |
| .ent       | text/xml                |                                                              |
| .fo        | text/xml                |                                                              |
| .htc       | text/x-component        |                                                              |
| .html      | text/html               |                                                              |
| .htx       | text/html               |                                                              |
| .htm       | text/html               |                                                              |
| .htt       | text/webviewhtml        |                                                              |
| .jsp       | text/html               |                                                              |
| .math      | text/xml                |                                                              |
| .mml       | text/xml                |                                                              |
| .mtx       | text/xml                |                                                              |
| .plg       | text/html               |                                                              |
| .rdf       | text/xml                |                                                              |
| .rt        | text/vnd.rn-realtext    |                                                              |
| .sol       | text/plain              |                                                              |
| .spp       | text/xml                |                                                              |
| .stm       | text/html               |                                                              |
| .svg       | text/xml                |                                                              |
| .tld       | text/xml                |                                                              |
| .txt       | text/plain              | 纯文字内容                                                   |
| .uls       | text/iuls               |                                                              |
| .vml       | text/xml                |                                                              |
| .tsd       | text/xml                |                                                              |
| .vcf       | text/x-vcard            |                                                              |
| .vxml      | text/xml                |                                                              |
| .wml       | text/vnd.wap.wml        |                                                              |
| .wsdl      | text/xml                |                                                              |
| .wsc       | text/scriptlet          |                                                              |
| .xdr       | text/xml                |                                                              |
| .xql       | text/xml                |                                                              |
| .xsd       | text/xml                |                                                              |
| .xslt      | text/xml                |                                                              |
| .xml       | text/xml                |                                                              |
| .xq        | text/xml                |                                                              |
| .xquery    | text/xml                |                                                              |
| .xsl       | text/xml                |                                                              |
| .xhtml     | text/html               |                                                              |
| .odc       | text/x-ms-odc           |                                                              |
| .r3t       | text/vnd.rn-realtext3d  |                                                              |
| .sor       | text/plain              |                                                              |

#### Audio Type

| 文件扩展名 | Content-Type(Mime-Type)   | 描述                                                         |
| :--------- | :------------------------ | :----------------------------------------------------------- |
| .acp       | audio/x-mei-aac           |                                                              |
| .aif       | audio/aiff                |                                                              |
| .aiff      | audio/aiff                |                                                              |
| .aifc      | audio/aiff                |                                                              |
| .au        | audio/basic               |                                                              |
| .la1       | audio/x-liquid-file       |                                                              |
| .lavs      | audio/x-liquid-secure     |                                                              |
| .lmsff     | audio/x-la-lms            |                                                              |
| .m3u       | audio/mpegurl             |                                                              |
| .midi      | audio/mid                 |                                                              |
| .mid       | audio/mid                 |                                                              |
| .mp2       | audio/mp2                 |                                                              |
| .mp3       | audio/mp3                 |                                                              |
| .mp4       | audio/mp4                 | MP4，全称MPEG-4 Part 14，是一种使用MPEG-4的多媒体计算机文件格式，扩展名为.mp4，以存储数字音频及数字视频为主。 |
| .mnd       | audio/x-musicnet-download |                                                              |
| .mp1       | audio/mp1                 |                                                              |
| .mns       | audio/x-musicnet-stream   |                                                              |
| .mpga      | audio/rn-mpeg             |                                                              |
| .pls       | audio/scpls               |                                                              |
| .ram       | audio/x-pn-realaudio      |                                                              |
| .rmi       | audio/mid                 |                                                              |
| .rmm       | audio/x-pn-realaudio      |                                                              |
| .snd       | audio/basic               |                                                              |
| .wav       | audio/wav                 |                                                              |
| .wax       | audio/x-ms-wax            |                                                              |
| .wma       | audio/x-ms-wma            |                                                              |

#### Video Type

| 文件扩展名 | Content-Type(Mime-Type) | 描述                                                         |
| :--------- | :---------------------- | :----------------------------------------------------------- |
| .asf       | video/x-ms-asf          |                                                              |
| .asx       | video/x-ms-asf          |                                                              |
| .avi       | video/avi               |                                                              |
| .IVF       | video/x-ivf             |                                                              |
| .m1v       | video/x-mpeg            |                                                              |
| .m2v       | video/x-mpeg            |                                                              |
| .m4e       | video/mpeg4             |                                                              |
| .movie     | video/x-sgi-movie       |                                                              |
| .mp2v      | video/mpeg              |                                                              |
| .mp4       | video/mpeg4             | MP4，全称MPEG-4 Part 14，是一种使用MPEG-4的多媒体计算机文件格式，扩展名为.mp4，以存储数字音频及数字视频为主。 |
| .mpa       | video/x-mpg             |                                                              |
| .mpe       | video/x-mpeg            |                                                              |
| .mpg       | video/mpg               |                                                              |
| .mpeg      | video/mpg               |                                                              |
| .mps       | video/x-mpeg            |                                                              |
| .mpv       | video/mpg               |                                                              |
| .mpv2      | video/mpeg              |                                                              |
| .wm        | video/x-ms-wm           |                                                              |
| .wmv       | video/x-ms-wmv          |                                                              |
| .wmx       | video/x-ms-wmx          |                                                              |
| .wvx       | video/x-ms-wvx          |                                                              |

#### Image Type

| 文件扩展名 | Content-Type(Mime-Type) | 描述                                                         |
| :--------- | :---------------------- | :----------------------------------------------------------- |
| .tif       | image/tiff              | 标签图像文件格式（Tagged Image File Format，简写为TIFF）是一种主要用来存储包括照片和艺术图在内的图像的文件格式。它最初由Aldus公司与微软公司一起为PostScript打印开发。 |
| .fax       | image/fax               |                                                              |
| .gif       | image/gif               | 图像互换格式（GIF，Graphics Interchange Format）是一种位图图形文件格式，以8位色（即256种颜色）重现真彩色的图像。 |
| .ico       | image/x-icon            |                                                              |
| .jfif      | image/jpeg              |                                                              |
| .jpe       | image/jpeg              |                                                              |
| .jpeg      | image/jpeg              | JPEG是一种针对相片图像而广泛使用的一种有损压缩标准方法。     |
| .jpg       | image/jpeg              |                                                              |
| .net       | image/pnetvue           |                                                              |
| .png       | image/png               | 便携式网络图形（Portable Network Graphics，PNG）是一种无损压缩的位图图形格式，支持索引、灰度、RGB三种颜色方案以及Alpha通道等特性。 |
| .rp        | image/vnd.rn-realpix    |                                                              |
| .tif       | image/tiff              |                                                              |
| .tiff      | image/tiff              |                                                              |
| .wbmp      | image/vnd.wap.wbmp      |                                                              |

#### Message Type

|  文件扩展名 | Content-Type(Mime-Type) |
| :--------- | :---------------------- |
| .eml       | message/rfc822          |
| .mht       | message/rfc822          |
| .mhtml     | message/rfc822          |
| .nws       | message/rfc822          |

#### Drawing Type

|  文件扩展名 | Content-Type(Mime-Type) |
| :--------- | :---------------------- |
| .907       | drawing/907             |
| .slk       | drawing/x-slk           |
| .top       | drawing/x-top           |

#### Java Type

|  文件扩展名 | Content-Type(Mime-Type) |
| :--------- | :---------------------- |
| .class     | java/*                  |
| .java      | java/*                  |

#### Other Type

|  文件扩展名 | Content-Type(Mime-Type) |
| :--------- | :---------------------- |
| .dwf       | Model/vnd.dwf           |