# AWeChat
#ZongRui，Li
h mimic WeChat, iOSAppTemplate code refactoring.This version of TLChats is based on [TLKit] (Https://github.com/tbl00c/TLKit), [ZZFLEX] (Https://github.com/tbl00c/ZZFLEX) Implementation.
<img src='. /Screenshot/1.PNG'width ='375' height ='667'alt='screenshot1' align=center /> <img src='. /Screenshot/2.PNG'width ='375' height ='667'alt='screenshot2' align=center />
<img src='. /Screenshot/3.PNG'width ='375' height ='667'alt='screenshot3' align=center /> <img src='. /Screenshot/5.png'width ='375' height ='667'alt='screenshot4' align=center />
<img src='. /Screenshot/4.png'width ='375' height ='667'alt='screenshot4' align=center /> <img src='. /Screenshot/6.png'width ='375' height ='667'alt='screenshot5' align=center /
##Recent Plan
The project structure will be sorted out in the near future, and the entire project will be modularized at the code level, mainly including:
* Chat interface rebuilding, logically independent;
* Primary control class logic collation;
* Major lists are refactored with ZZFLEX to increase their extensibility;
* ZZFLEX encapsulates a UIKit layer, mainly including a data-driven list framework, and chain extensions of commonly used controls in UIKit. ZZFLEX-related data is being collated and is currently being sourced.
* iOS11 adapter;
*Other functional improvements.

##Implemented functionality

1. Message Interface
*Message List (New Session Join, DB)
*Message Side Slide Delete
*Friend Search (supports fuzzy queries)
*More menus (items_can be customized dynamically)

2. Address Book Interface
*Friends list (grouping algorithm, DB)
*Friend Search
*Friend profile (UI Abstract template), data settings UI (using settings class UI template)
*New friends (read mobile contact information)
*Group Chat (UI, DB)
*Label (UI, Logic)

3. Discovery interface (using menu class UI template)
*Circle of friends (overall architecture, partial UI)
*Sweep (UI, 2D Code Scan, Barcode Scan)
*Shake UI
*Bottle UI
*Shopping, games (encapsulated WebView)

4. My interface (using menu class UI template)
*Personal Information (using Settings Class UI Template)
*Emotions (UI, network requests, downloads, management)
*Settings (abstract settings class UI generic template)
*Font Size
*Chat Background
*My expression
*Empty chat log

5. Chat interface
*Chat Input Box
*Message Display View
*Text message
*Picture message
*Emotional message
*Voice message
*Chat Keyboard
*Emotional keyboard (dynamic add-delete emoticon pack)
*More keyboards
*Chat Record Store (DB)

Functions in ##Plan
1. Chat interface: video message
2. Chat interface: geographic location messages
3. Circle of Friends: CoreText implements friend compliment and reply function
4. Chat module pull-out

Third-party libraries used primarily by ##projects
* [Masonry] (Https://github.com/SnapKit/MasonryAutomatic layout framework, simple and efficient
* [FMDB] (Https://github.com/ccgus/fmdb):sqlite database management framework
* [AFNetworking] (Https://github.com/AFNetworking/AFNetworking: Network requests
* [SDWebImage] (Https://github.com/rs/SDWebImage: Network picture download, caching
* [JExtension] (Https://github.com/CoderMJLee/MJExtension):JSON-Model Interchange Framework, High Efficiency and Low Coupling
* [MJRefresh] (Https://github.com/CoderMJLee/MJRefresh: Drop-down refresh, pull-up load more, inherit simple
* [CocoaLumberjack] (Https://github.com/CocoaLumberjack/CocoaLumberjackLog Rating, Localization
* [MWPhotoBrowser] (Https://github.com/mwaterfall/MWPhotoBrowser: Picture selector
* [SVProgressHUD] (Https://github.com/SVProgressHUD/SVProgressHUD): Progress Tip Box