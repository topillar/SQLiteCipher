# SQLiteCipher
sln for SQLite3 Cipher using wxSQLite3 sources, simply create .dll file and .lib file both.

mark for memo:

<PreprocessorDefinitions>SQLITE_HAS_CODEC;CODEC_TYPE=CODEC_TYPE_AES128;SQLITE_CORE;SQLITE_SECURE_DELETE;SQLITE_ENABLE_COLUMN_METADATA;SQLITE_ENABLE_RTREE;WIN32;_DEBUG;_WINDOWS;_USRDLL;SQLITECIPHER_EXPORTS;%(PreprocessorDefinitions)</PreprocessorDefinitions>

<PreprocessorDefinitions>SQLITE_API=__declspec(dllexport);_DEBUG;_WINDOWS;_USRDLL;SQLITECIPHER_EXPORTS;%(PreprocessorDefinitions)</PreprocessorDefinitions>
