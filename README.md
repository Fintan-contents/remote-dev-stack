# 複数ロケーションに跨るチーム向けの開発環境・実行環境のスタック

我々は東京と大阪の2ロケーションに跨ったチームで、スタートアップと協業してサービス開発を行っています。

異なるロケーションに居るチームメンバーとは気軽に会話することは不可能ですが、同じチームで開発を進めるためにはリアルタイムなコミュニケーションは必要不可欠です。

またサービス開発ではサービスのPoC（Proof of Concept）を実施する際、スマートフォンやIoT機器からインターネットを通じてAPIへアクセスする必要があり、広くアクセス可能な実行環境を必要としました。

そのためロケーションの制約を受けずにリアルタイムなコミュニケーションを取りながら開発を進めるための開発環境と、PoCなどで広くアクセス可能な実行環境を、クラウドサービスを利用して構築しました。

更に開発環境はアクセス制御や侵入者対策などを目的に、VPNを介してアクセスするようにしています。

このドキュメントでは、それら「開発環境のスタック」と「実行環境のスタック」を、具体的な活用方法も含めて紹介します。

- [環境の全体構成](./docs/structure.md)
- [開発環境・実行環境のスタック紹介](./docs/tools.md)
- [スクラム開発における開発環境スタックの活用について](./docs/scrum.md)

## ライセンス

![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)<br/>
本ドキュメントは[クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス](http://creativecommons.org/licenses/by-sa/4.0/)の下に提供されています。
