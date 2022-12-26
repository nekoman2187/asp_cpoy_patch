# 変更ディレクトリ[asp/arch/rx_gcc/rx72n]  
変更したファイルを以下に示す 
<br>  
|変更ファイル|変更点概略|
|:--|:--|
./asm_config.h   | 　変更なし
./Makefile.prc	|	rx63n_config.o -> rx72n_config.o rx63n_support.o -> rx72n_support.o
./MANIFEST		|	RX63N->RX72N　文字列変更
./prc.tf		|	RX63N->RX72N　文字列変更
./prc_stddef.h	|	TOPPERS_RX63N->TOPPERS_RX72N　プロセッサ略称文字列変更
./prc_syssvc.h  |　変更なし
./prc_user.txt  |　変更なし
./rx72n.h		|	RX63N->RX72N　文字列変更 EDMAC割り込み番号変更/CMT2 割り込み番号変更(ファイル名変更)
./rx72n.tf		|	RX63N->RX72N　文字列変更 割り込み番号列変更(ファイル名変更)
./rx72n_config.c |	EDMAC割り込み予約番号変更(ファイル名変更)
./rx72n_config.h |	RX63N->RX72N　文字列変更(ファイル名変更)
./rx72n_elf.ld   | 　変更なし(ファイル名変更)
./rx72n_support.c |　変更なし(ファイル名変更)
./rx72n_support.h |　変更なし(ファイル名変更)
./start.S		|	不要な初期化を削除
<br>  