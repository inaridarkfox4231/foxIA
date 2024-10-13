# foxIA
foxIA公開してみようかしら  
cdn: https://inaridarkfox4231.github.io/foxIA/foxIA.js  
  
ふぉっくすあいえー（読み方）  
  
キャンバスのインタラクションを柔軟に記述するための自分用ライブラリ  
他の人が使いやすいかどうかは分かんないです  
インスパイア元：  
p5.EasyCam：https://github.com/freshfork/p5.EasyCam  
pavelさんの流体シミュレーション（ポインターの概念はここから拝借した）：  
  https://github.com/PavelDoGreat/WebGL-Fluid-Simulation  
ピンチイン、ピンチアウトが楽に記述できるのはセールスポイントかもしれないです。  
  
応用：sayoさんの3D Drawing：https://openprocessing.org/sketch/2277705  
PointerPrototypeの継承という、数ある使い方のうちの一つを使って記述することで、  
マウス、タッチ、スタイラスペンのいずれでも同じように動作する処理が書けました。  
スマホだとマルチタッチが可能です。複数の箇所で同時に動作します。  

マウススクロールで位置計算がバグるのを修正(2024/10/14)  

なんか公開したとたんに大したことない気がしてきた  
まあ自分が使って便利ならそれでいいか  

ひとつだけ  
p5.jsでは現在、mousePressed()ではタッチ操作の代わりができなくなっています。  
詳しくは：https://github.com/processing/p5.js/issues/7195
  
