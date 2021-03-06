NinjaTrader history exporter
============================
This tool is designed for bulk exporting market data bars from NinjaTrader 7, overcoming the application limitations that require exporting one instrument at a time.


## Usage
NinjaTraderDataExporter [-in=*input dir*] [-out=*output dir*] [-sep=*separator*] [-noheader]

  -in:&lt;input dir&gt;	- Directory to read files from. If not specified, will default to _**&lt;My Documents&gt;\NinjaTrader 7\db\minute\**_

  -out:&lt;output dir&gt; - Directory to write output to. Defaults to _**C:\Temp\NTHistoryExport**_ if not specified.

  -sep:&lt;separator&gt; - Separator for fields. Defaults to ';' (NinjaTrader export format) if not specified.

  -noheader - Exclude header row from output files

  -?/help - Print usage instructions
  
  
## Licence
Permission is hereby granted to distribute, export, modify and otherwise alter this software
in any way, shape, or form as desired. No warranty is granted, either express or implied.
Build and run at your own risk.


### Note
This software is in no way affiliated with NinjaTrader LLC, makers of the NinjaTrader software. Registered trademarks are the property of their respective owners.
