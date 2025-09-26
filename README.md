# DIY PCE Card

## Overview

PC Engine homebrew.4Mbit Flash memory card and writer.

## Files

・pce_card1.comp : memory card's PCB CAD data(CADLUS X).

・pce_wr.comp : writer's PCB CAD data(CADLUS X).

・wr.prg : Writing software(Pi STARTER).Raspberry Pi4以降で動作不可能なので注意。

・wr_fc.py : Writing software(Python).FC/GB/PCE共通です。Raspberry Pi4以降でも動作します。

https://github.com/nicotakuya/diyfccartridge/blob/main/wr_fc.py

## Parts
Card

・(U1) 4Mbit フラッシュメモリ SST39SF040-70-4C-PHE

Writer

・(U1/U2)I/Oエキスパンダ https://akizukidenshi.com/catalog/g/gI-10644/

・(U3)三端子レギュレータ48M05 https://akizukidenshi.com/catalog/g/gI-00451/

・(U4)74HC32	  https://akizukidenshi.com/catalog/g/gI-12877/

・(D1/D2)ダイオード	 

・(LED1/2/3)LED	 

・(CN1)PCエンジン(HuCard)用のコネクタ	 

・(CN2)2x20pinピンヘッダ	 

・(R1/2/3/4)抵抗

## images

![pce_card](https://user-images.githubusercontent.com/5597377/131228920-34a01e38-0645-4db0-aa4e-b4ba0f52f619.png)
![pce_wr](https://user-images.githubusercontent.com/5597377/131228988-7d922856-d1d2-4879-8a75-f74ee6f65cd5.png)

## movie

https://www.youtube.com/watch?v=CV6kTOanBV0
