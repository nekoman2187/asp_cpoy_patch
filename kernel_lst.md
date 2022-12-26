# 変更ディレクトリ[asp/kernel]  
変更したファイルを以下に示す 
<br>  
|変更ファイル|変更点概略|
|:--|:--|asp/kernel
./interrupt.c  | dis_int/ena_int Renesas BSP とコンフリクトする為 undef
./kernel_impl.h　| #define EXTERNAL_INIT 外部初期化(Renesas BSPによる）定義define追加
<br>  