## Hi, I'm nerfnyanit 👋
フルスタックエンジニアを目指して学習・個人開発を行っています。
フロントエンドは React / Next.js / TypeScript を自主学習し、インフラ・ネットワーク領域では資格取得を通じて基礎を固めています。
資格で学んだ Linux / AWS の知識を使い、自分の Next.js ポートフォリオを **AWS EC2 に HTTPS で公開**しました。
現在は **CCNA** の学習中です。

---

## 🛠 Tech Stack

**Frontend**
- React
- Next.js（App Router）
- TypeScript

**Infrastructure / Network**
- AWS（EC2 / セキュリティグループ / Elastic IP / Budgets）
- Linux（AlmaLinux 9・RHEL 系 / SELinux / firewalld / systemd）
- Nginx（リバースプロキシ / HTTPS 終端）、Let's Encrypt
- ネットワーク基礎（CCNA学習中）

**Styling**
- Tailwind CSS
- CSS Modules

**Tools**
- Git / GitHub
- VS Code

---

## 📜 Certifications
- AWS Certified Cloud Practitioner（CLF-C02）
- LinuC Level 1
- CCNA（学習中）

---

## 🚀 Projects

### 🔹 Linux Server Lab（Linuxサーバー構築ポートフォリオ）
Linux サーバーを一人で構築し、Next.js のポートフォリオを AWS EC2 に HTTPS で公開するまでを、つまずいた点も含めて記録したポートフォリオです（10 日間・費用 0 円）。
- **多層防御**：SG・firewalld・SELinux（Enforcing のまま）に加え、Next.js を `127.0.0.1` だけで待ち受けさせ、外の入口を Nginx だけにした
- **障害対応**：SELinux による 502 を `ausearch` で特定して解決。さらに手元の VM で 5 つの障害をわざと起こし、自力で切り分けて直した
- **ドキュメント**：構成図、「なぜそうしたか」、障害記録、ゼロから公開するまでの手順書
- 使用技術：AlmaLinux 9 / AWS EC2 / Nginx / SELinux / firewalld / systemd / Let's Encrypt
- GitHub：https://github.com/nerfnyanit/linux-server-lab

---

### 🔹 Portfolio Site
自己紹介と制作物をまとめたポートフォリオサイトです。上の Linux Server Lab で構築した EC2 で公開しています。
- 使用技術：Next.js / TypeScript / Tailwind CSS
- サイト：https://nerfnyanit-portfolio.duckdns.org
- GitHub：https://github.com/nerfnyanit/frontend-portfolio

---

### 🔹 個人開発・学習プロジェクト
- React / Next.js の理解を深めるための小規模アプリ開発
- コンポーネント設計・状態管理を意識した実装
- フロントエンド／バックエンドを分離した構成に挑戦中

---

## 📘 Learning & Policy
- 写経で終わらせず、自分で考えて実装することを重視
- 「なぜ動くのか」を調べながら理解を深める
- 小さくても最後まで完成させることを意識
- フロントエンドだけでなく、**アプリ全体の仕組みを理解すること**を大切にしている

---

## 📌 Currently
- CCNA の学習
- React / Next.js / TypeScript の自主学習・個人開発を継続中
- EC2 の更新手順をシェルスクリプトにまとめて自動化する

---

## 🎯 Next Challenge
フロントエンドからサーバー・ネットワークまで、アプリが動く仕組みを一通り自分の手で作れるフルスタックエンジニアを目指しています。
次は、バックエンド（API）と DB を追加したフルスタック構成と、Terraform による AWS 構成のコード管理に挑戦する予定です。

---

## 📫 Contact
- GitHub: https://github.com/nerfnyanit
- Gmail: nerfnyanit@gmail.com
- X (Twitter): https://x.com/nerfnyanit
