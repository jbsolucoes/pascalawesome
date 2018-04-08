# Pascal Awesome
Delphi / Lazarus / FPC

General Libraries

*   [JVCL](http://sourceforge.net/projects/jvcl). Library of over 600 Delphi components developed by "Project JEDI" members. // GUI, algorithms, classes, API headers etc.
*   [Alcinoe](http://sourceforge.net/projects/alcinoe). Components suite for Delphi. // Network: FTP/Http/NNTP/POP3/SMTP, ISAPI, WinInet Http/FTP clients; DB: Firebird/MySQL/SQLite3/Memcached/MongoDb/SphinxQL; XML/JSON Parser; ZLIB; Cryptography: AES, Blowfish, MD5, SHA, secure keyed MD5/SHA; Other: Self-Balancing Binary Trees, expression evaluator
*   [Fundamentals Code Library](http://sourceforge.net/projects/fundementals). Collection of Delphi / FreePascal code units. Includes libraries for Unicode, Strings, Data Structures, Sockets and Mathematics. // Utils: ZLIB compression; JSON; XML; ProtocolBuffers; Hashes: XOR, CRC, Adler, MD5, SHA, secure keyed MD5/SHA, etc; Network: bYou must click thanks to see this content... optional support).
*   [TForge](https://bitbucket.org/sergworks/tforge). Open-source crypto library written in Delphi, compatible with Free Pascal Compiler. MD5, SHA1, SHA256, CRC32, Jenkins-One-At-Time, HMAC, PBKDF1, PBKDF2, AES, DES, RC4, RC5, Salsa20.  
    

XML/JSON

*   [OmniXML](http://code.google.com/p/omnixml). XML parser written in Delphi. Full support for Document Object Model (DOM) Level 1 specification; Supports Extensible Markup Language (XML) 1.0 (Second Edition) specification; Has built-in support for different code pages (main 8-bit code pages, UTF-8, UTF-16); Is compatible with MS XML parser; Fast parsing even large and highly structured documents; Includes helper functions to ease processing XML documents; Simplified XPath support.
*   [SAX for Pascal](http://sourceforge.net/projects/saxforpascal). Designed to implement the Simple API for XML Parsing in Pascal/Delphi. //Callback-based XML parser, useful for processing huge XML streams.
*   [KDS XML](http://sourceforge.net/projects/kdsxml). Class library for streamed parsing, validating and generating XML. It is written in Object Pascal/Delphi and works on Win32 (Delphi) and Linux (Kylix). Parts of it depend on the SAX for Pascal interface specifications.
*   [XML Partner](http://sourceforge.net/projects/tpxmlpartner). Helps add the power of XML to Borland Delphi, C++ Builder, and Kylix projects through native, easy to use VCL and CLX components. These powerful components simplify the process of creating, modifying, and parsing XML data documents. // Seems dead, check out [this](http://www.songbeamer.com/delphi)page for probably newer version.
*   [Open XML](http://www.philo.de/xml/downloads.shtml). Provides a wide range of methods, components and foundation classes. It can be used for Win32/Kylix as well as for .NET development.
*   [SuperObject](https://github.com/hgourvest/superobject). Parser/writer for JSON data format. This toolkit is designed to work with Delphi and FreePascal (win32, win64, linux32, linux64, MacOSX Intel)
*   [OXml](http://www.kluug.net/oxml.php). New XML library for Delphi and Lazarus, developed in late 2013. I took some inspiration from OmniXML but wrote the library completely from scratch. The aim of OXml is to be the most versatile and fastest XML library for the Pascal language. OXml features a SAX parser, DOM implementation, a sequential DOM parser a direct XML reader/writer and a vendor for Delphi's XmlIntf.TXMLDocument. OXml supports all Delphi versions starting from Delphi 4 on all platforms: Win32, Win64, OSX, iOS, Android. OXml supports Lazarus 1.0 and newer on all platforms (tested Win32, Win64, Linux, MacOSX).
*   [Libxml2 for pascal](https://sourceforge.net/projects/libxml2-pas). Pascal units accessing the popular XML API from Daniel Veillard. This should be usable at least from Kylix and Delphi, but hopefully also from other Pascal compilers (like freepascal).
*   [NativeXml](https://code.google.com/p/simdesign). This component contains a small-footprint Object Pascal (Delphi) XML implementation that allows to read and write XML documents. You basically only need one unit and you can simply add it to the "uses" clause. You can use this software to read XML documents from files, streams or strings. The load routine generates events that can be used to display load progress on the fly. You can also use it to create and save XML documents.
*   [Chimera](http://code.google.com/p/jsonchimera). Open Source (MIT License) library for Delphi XE2 which provides a fast and cross platform JSON generator/parser (serializer/deserializer) under a license that doesn't suck.
*   [SynCommons](https://github.com/synopse/mORMot/blob/master/SynCommons.pas). High speed JSON library, using   
          
    Code:  
    
    `TDocVariant` (custom variant type for storage and access)
    
*   [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas). High speed cross-platform JSON library, using   
          
    Code:  
    
    `TDocVariant` (custom variant type for storage and access)    

LanguageTools for Pascal and other languages

*   [Next Delphi Yacc & Lex](https://github.com/RomanYankovsky/ndyacclex). Parser generator toolset for Delphi.
*   [Abstract Syntax Tree Builder](https://github.com/RomanYankovsky/DelphiAST). With DelphiAST you can take real Delphi code and get an abstract syntax tree. One unit at time and without a symbol table though.
*   [Castalia-Delphi-Parser](https://github.com/jacobthurman/Castalia-Delphi-Parser). These files make up a hand-written high speed parser for the Object Pascal dialect known as "Delphi". The original work was done by Martin Waldenburg in the late 1990s, and the project was abandoned sometime before 2003, when I found the code and began working on it. I have kept it updated as necessary to work with my project, called "Castalia".  
    

SystemLow-level helper stuff: memory, threading etc

*   [FastMM](http://sourceforge.net/projects/fastmm). Lightning fast replacement memory manager for Embarcadero Delphi Win32 and Win64 applications that is not prone to memory fragmentation, and supports shared memory without the use of external .DLL files. // Used as stock memory manager since 2006 but in simplified version. Provides powerful memory leak/corruption detection instruments.
*   [OmniThreadLibrary](https://github.com/gabr42/OmniThreadLibrary). Simple to use threading library for Delphi. // Easy integration of async processes in your app
*   [ScaleMM](https://github.com/andremussche/scalemm). Fast scaling memory manager for Delphi
*   [Delphi Detours Library](https://github.com/mahdisafsafi/delphi-detours-library). Library allowing you to hook Delphi functions and object methods and Windows API functions. It provides an easy way to insert and remove hook. // Supports x64, calling original functions, multi hooks, COM/Interfaces/win32api, object methods hooking, fully thread-safe, Delphi 7/2005-2010/XE-XE7 & Lazarus/FPC, 64 bit address is supported.
*   [MemoryModule](https://github.com/Fr0sT-Brutal/Delphi_MemoryModule). With the MemoryModule engine you can store all required DLLs inside your binary to keep it standalone. Additional hook units allow transparent using of MM engine thus allowing switching MM/WinAPI loading as well as enabling 3rd party dynamic-load DLL interfaces that are unaware of MM (tested with Interbase Express components and Firebird client library). MemoryModule is a Pascal port of Joachim Bauch's C MemoryModule.  
    

Other non-visual

*   [TRegExpr](http://regexpstudio.com/TRegExpr/TRegExpr.html). Easy to use and powerful tool for sophisticated search and substitutioning and for template-based text input check. // Abandoned since 2004 but unlike stock RAD Studio implementation doesn't use PCRE obj files that add dependency on msvcrt.dll
*   [FLRE](https://github.com/BeRo1985/flre). FLRE ( F ast L ight R egular E xpressions) is a fast, safe and efficient regular expression library, which is implemented in Object Pascal (Delphi and Free Pascal) but which is even usable from other languages like C/C++ and so on.
*   [OnGuard](http://sourceforge.net/projects/tponguard) ([Alternate](https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users. // Second link points to an adapted version for newest compiler versions.
*   [StringSimilarity](https://github.com/chaosben/theunknownones). Package designed for some fuzzy and phonetic string comparison algorithms. So far implemented are the following algorithms: DamerauLevenshtein, Koelner Phonetik, SoundEx, Metaphone, DoubleMetaphone, NGram, Dice, JaroWinkler, NeedlemanWunch, SmithWatermanGotoh, MongeElkan.
*   [STOMP Client](https://github.com/danieleteti/delphistompclient). STOMP client for Embarcadero Delphi and FreePascal. The project can use INDY (Delphi) or Synapse (Delphi or FreePascal).
*   [PubSub Chimera](https://code.google.com/p/pubsubchimera). Open Source (MIT License) library for Delphi which provides a fast and cross platform PubSub and Message Queue implementation under a license that doesn't suck.
*   [DuckDuckDelphi](https://code.google.com/p/duckduckdelphi). Adds simple duck typing to Delphi Objects and provides an RTTI helper class to simplify many common RTTI tasks.
*   [byterage](https://github.com/quartexNOR/byterage). Object pascal class library designed to remove some of the limitations of streams. The framework is very simple to use, with only one common ancestor class (TBRBuffer) which defines a set of storage agnostic mechanisms for allocating, scaling, inserting, deleting and otherwise manipulating a segment of raw binary data.
*   [stateless](https://github.com/SirRufo/stateless). Simple library for creating state machines in Delphi code.  
    

OSTools that help dealing with OS-specific internals

*   [GLibWMI](http://sourceforge.net/projects/glibwmi). Component Library for Delphi that encapsulate the classes for access to WMI of Windows in a set of VCL. BiosInfo, PrinterInfo, DiskInfo,... Allow access WMI Classes: WIN32\_Bios, WIN32\_Printers, WIN32_DiskDrive.
*   [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap). Set of classes to get all the info about a memory of a running process.
*   [The new Drag and Drop Component Suite](https://github.com/landrix/The-new-Drag-and-Drop-Component-Suite-for-Delphi). VCL component library that enables your Delphi and C++Builder applications to support COM based drag and drop and integrate with the Windows clipboard.
*   [TSMBIOS](https://github.com/RRUZ/tsmbios). Allows access the System Management BIOS (SMBIOS) using the Object Pascal language (Delphi or Free Pascal). The SMBIOS (System Management BIOS) is a standard developed by the DMTF. The information stored in the SMBIOS includes devices manufacturer, model name, serial number, BIOS version, asset tag, processors, ports and device memory installed.  
    

Unit Testing

*   [DUnitX](https://github.com/VSoftTechnologies/DUnitX). New test framework, taking ideas from DUnit, NUnit and other test frameworks. It is designed to work with Delphi 2010 or later, it makes use of language/RTL features that are not available in older versions of Delphi.
*   [DUnit](http://dunit.sourceforge.net/). Unit Testing Framework, that has been the standard testing framework for years, the Delphi IDE now ships with this library. In addition to the drag and drop components, the Drag and Drop Component Suite also includes components that can be used to build Windows Shell Extensions.
*   [DUnit2](http://dunit2.sourceforge.net/). Fork of the DUnit Project that adds several new features.
*   [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec). Library for running automated tests written in plain language. Because they're written in plain language, they can be read by anyone on your team. Because they can be read by anyone, you can use them to help improve communication, collaboration and trust on your team.
*   [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks). Simple mocking framework for Delphi XE2 or later. Allow you to mock both classes and interfaces for testing.
*   [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML). Test runner that allows DUnit Tests to output NUnit compatible XML.  
    

UtilitiesUseful dev tools/IDE plugins

*   [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads/downloads). Build tool for Delphi. Recompile projects/packages from sources with all dependencies, without need to mess around with configs. Quickly (re-)install components from sources into IDE, with no need to change your Library Path. // Powerful automating tool. Freeware but not open source
*   [Delphi IDE theme editor / Delphi IDE Colorizer](https://github.com/rruz/delphi-ide-theme-editor). Tool to change the IDE color highlighting of several Object Pascal IDE's like Delphi (RAD Studio), Appmethod, Lazarus and Smart Mobile Studio. DITE supports Delphi 5-7, 2005-2010, XE-XE8, Appmethod 1.13-1.14, Lazarus v1.0.1.3 and Smart Mobile Studio IDE v1.1.2.17. The Delphi IDE Colorizer (DIC) is a plugin which allows to customize the look and feel of the workspace of the RAD Studio IDE and Appmethod.
*   [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions). Extends the Delphi/C++Builder IDE by adding some new productivity features //Many useful IDE tweaks, must have.
*   [VCL Fix Pack](http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10). Delphi unit that fixes VCL and RTL bugs at runtime by patching the original functions. If you want all IDE Fix Pack fixes in your application this unit is what you are looking for. Adding the unit to your project (Delphi and C++Builder) automatically installs the patches that are available for your Delphi/C++Builder version. // Actual for Delphi/C++ 6..2009
*   [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack). Collection of unofficial bug fixes and performance optimizations for the RAD Studio IDE, Win32/Win64 compiler and Win32 debugger. IDE Fix Pack is an IDE plugin for RAD Studio 2009-XE6 that fixes IDE bugs at runtime. All changes are done in memory. No files on disk are modified. None of your projects are modified or benefit from the IDE Fix Pack other than being compiled faster. Only the IDE gets the fixes and optimizations. // Supports all RAD Studio versions since 2007. Removes lots of annoying bugs that EMBT haven't fixed for years. Yay!
*   [GExperts](https://sourceforge.net/projects/gexperts). Free set of tools built to increase the productivity of Delphi and C++Builder programmers by adding several features to the IDE. GExperts is developed as Open Source software and we encourage user contributions to the project. Grep search and replace supporting unicode files, DFMs, etc; Automatically rename components, insert text macros, open recent files; Easily backup your projects, with custom additional file lists; Keep nested lists of favorite files for quick access; Track dependencies between units in your project; Quickly jump to any procedure in the current unit; And much, much more...
*   [CnWizards](https://github.com/cnpack). Free Plug-in Tool Set for Delphi/C++ Builder/CodeGear RAD Studio to Improve Development Efficiency.
*   [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi). Tool which aids you installing components to your Delphi IDE. DelphiPI automatically resolves dependencies between packages, compiles, installs and adds source paths to your IDE.
*   [ResEd](https://github.com/chaosben/theunknownones). Expert for Delphi 2005, 2006, 2007, 2009, 2010 and XE. This expert is designed for editing the resource files (.res; .resx) that are linked to the active project. It will automatically search for all occurrences of {$R xyz.res} lines and will open/create resourcefiles for them. The expert registers itself in the menubar of Delphi under View.
*   [Inno Setup](http://www.jrsoftware.org/isinfo.php). Free installer for Windows programs. First introduced in 1997, Inno Setup today rivals and even surpasses many commercial installers in feature set and stability.
*   [SynProject](https://github.com/synopse/SynProject) ([docs](http://synopse.info/fossil/wiki?name=SynProject)). Tool for code source versioning and automated documentation of Delphi projects.
*   [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.
*   [PasDoc](https://sourceforge.net/projects/pasdoc). Documentation tool for ObjectPascal (FreePascal and Delphi) source code. Documentation is generated from comments found in source code. Available output formats are HTML, HtmlHelp, LaTeX, latex2rtf, simplexml. More output formats may be added in the future.
*   [WMI Delphi Code Creator](https://github.com/RRUZ/wmi-delphi-code-creator). Allows you to generate Object Pascal, Oxygene, C++ and C# code to access the WMI (Windows Management Instrumentation) classes, events and methods. Also includes a set of tools to explorer and Query the content of the WMI.
*   [Delphi Preview Handler](https://github.com/RRUZ/delphi-preview-handler). Preview handler for Windows Vista ,7 and 8 which allow you read your object pascal, C++ and Assembly code with Syntax highlighting without open in a editor
*   [Delphi Dev. Shell Tools](https://github.com/RRUZ/delphi-dev-shell-tools). Windows shell extension with useful tasks for Object Pascal Developers (Delphi, Free Pascal).


Original source inspiration: http://www.delphifan.com Awesome Delphi Components Thread
