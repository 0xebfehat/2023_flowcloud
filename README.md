# USB flows in the Great River: IDA FLIRT signature & IOC
IDA Pro FLIRT signature for FlowCloud RAT component, "fcClientDll" and Indicators mentioned in my presentation "USB flows in the Great River".

You can check the presentation at [Virus Bulletin 2023 website.](https://www.virusbulletin.com/conference/vb2023/abstracts/usb-flows-great-river-classic-tradecraft-still-alive/)

- fcClientDll.sig 
  - This signature was created from the idb file which identifies fcClinetDll functions (I added prefix "fcClient_") and open source libraries (Protocol Buffers, Boost C++, ZThread, SQLite).
  - For more information about FLIRT: https://hex-rays.com/products/ida/tech/flirt/

- flowcloud_ioc_2023.csv
  - FlowCloud IOCs mentioned in the presentation.
