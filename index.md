# cuda-tutorial
これは主にR研の人々に向けたCUDA C/C++のTutorialですが、他の方にも参考になるように書いています。
基本的なCが書ける程度の力があれば読めるようにしているつもりです。

CUDAの日本語資料としては、他に例がないくらいなるべく体系的かつ詳細にわかりやすく書いたつもりですが、不明な点がございましたら遠慮なく連絡ください。なんなら感想でも構いません。

## 目次
章末課題もつけましたが、解答についてはまだ書けてないです。

1. [GPUの概要](./1.0.md)
    1. [GPUとは](./1.1.md)
    1. [GPUとCPU](./1.2.md)
    1. [GPUの構造](./1.3.md)
    1. [CUDAの概要](./1.4.md)
    1. [GPUとCUDAの関係](./1.5.md)
    1. [質問と回答](./1.6.md)
1. [CUDAの基本的な書き方](./2.0.md)
    1. [ホストとデバイス](./2.1.md)
    1. [デバイスコード](./2.2.md)
    1. [ホストコード](./2.3.md)
1. [Hello World by CUDA](./3.0.md)
    1. [Hello CUDA](./3.1.md)
    1. [GPUを使う](./3.2.md)
1. [ベクトル計算](./4.0.md)
    1. [逐次計算](./4.1.md)
    1. [並列計算](./4.2.md)
    1. [章末課題](./4.3.md)
    1. [解答例](./4.4.md)
1. [総和計算](./5.0.md)
    1. [Atomic演算](./5.1.md)
    1. [畳み込み法](./5.2.md)
    1. [Sharedメモリを活用した高速化](./5.3.md)
    1. [章末課題](./5.4.md)
    1. [解答例](./5.5.md)
1. [行列計算](./6.0.md)
    1. [並列化](./6.1.md)
    1. [章末課題](./6.2.md)
    1. [解答例](./6.3.md)
1. [乱数](./7.0.md)
    1. [逐次での疑似乱数生成](./7.1.md)
    1. [乱数生成の並列化](./7.2.md)
    1. [章末課題](./7.3.md)
    1. [解答例](./7.4.md)
1. [発展課題](./8.0.md)
    1. [砂粒を数える](./8.1.md)
    1. [拡散運動](./8.2.md)
    1. [拡散方程式](./8.3.md)
    1. [液体の運動](./8.4.md)
1. CPUの最適化

## Repository
このブログはGithub Pagesを用いて書かれています。
意見、不具合等ございましたら、以下のリポジトリにてissueを立てるか、私まで直接連絡するか、メール(件名の頭にcuda-tutorialを添えてください。)していただけますと幸いです。

GitHub: [https://github.com/PhysPeach/cuda-tutorial](https://github.com/PhysPeach/cuda-tutorial)

Mail: Masato.Shukawa「at」outlook.jp