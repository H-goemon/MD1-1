# MD1-1
## 仕様
・DCモーターを一つ、動かせます

・耐圧、ノイズ耐性ともに個体差あり，私の気まぐれで部品がくっついていない場合がある.

・三端子レギュレータを介さずに，駆動電源から信号電源を取れるようにするジャンパあり．

（IR2104の耐圧は25Vなので，6セルを用いて信号電源を取ってはならない．）

## 部品詳細仕様
・MOSFET：ものによって異なる
　　　　　 ニッケル水素電池で使用する分には，耐圧は気にしなくてよい．
      　　 
          リポを用いる場合は，耐圧も気にしながら使う必要がある．

・IR2104：ゲートドライバ

　　　　　 耐圧は25V，よって6セル使用時は三端子レギュレータ使用必須

・TLP152：フォトカプラ
　　　　　 耐圧は30V，よって6セル使用時は三端子レギュレータ使用

（リポバッテリーをつなぐときは，基本的に三端子レギュレータを使うのを推奨）
