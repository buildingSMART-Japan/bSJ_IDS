# 🏗️ Information Delivery Specification for BIM/CIM 積算

BIM/CIM積算に関するデータ連携で、Information Delivery Specification(IDS)による属性情報の設定または検査の可能性検証のため、IDSファイル（XML形式）を提供しています。

本リポジトリは、**buildingSMART Japan** によって公開されており、国土交通省は関与していません。

---

## 📛 バッジ

![License: CC-BY-NC-SA 4.0](https://img.shields.io/badge/License-CC--BY--NC--SA%204.0-lightgrey)
![Status: Maintained](https://img.shields.io/badge/status-maintained-brightgreen)
![Format: IDS XML](https://img.shields.io/badge/format-IDS%20XML-blue)

---

## 📚 目次

- [概要](#概要)
- [構成](#構成)
- [使い方](#使い方)
- [フォルダ構成](#フォルダ構成)
- [貢献方法](#貢献方法)
- [ライセンス](#ライセンス)
- [参照リンク](#参照リンク)

---

## 📝 概要

このリポジトリでは、IDS　仕様に準拠した XML ファイルを提供しています。

IDSファイルは、**国土交通省のBIM/CIM積算**において必要とされる**令和5年度の工事工種体系ツリーコード**に対応しており、各工種の3Dモデルに属性情報を明確に付与できるよう設計されています。

これにより、BIM/CIMモデルと設計数量管理機能のデータ連携が容易になり、属性情報の一貫性と利活用性が向上するか検証しています。

---

## 🗂️ 構成

各 IDS ファイルは、以下の工種に対応して分類されています：

- 道路新設・改築  
- 河川維持・修繕  
- 河川改修  
- 海岸整備  
- 共同溝・電線共同溝  
- 砂防・地すべり対策  
- 道路維持・修繕  

各フォルダには、関連する工種ごとの IDS ファイル（XML形式）が格納されています。

---

## 🚀 使い方

1. 任意の BIM/CIM モデルを作成し、IFC ファイルで書出しください。
2. BIM/CIM モデルに対応する IDS XML を選択します。
3. IDS ファイルのプロパティファセットのデータには複数登録されているので、適切な値を選択します。
3. IDS対応ツールで、モデルと IDS を照合します。
4. IDSファイルのアプリカビリティに適合するオブジェクトにリクワイヤメントのプロパティファセットを属性情報として設定します。

---

## 📁 フォルダ構成（例）

```
ids/
├── 道路新設・改築/（524ファイル）
├── 河川維持・修繕/（68ファイル）
├── 河川改修/（480ファイル）
├── 海岸整備/（174ファイル）
├── 共同溝・電線共同溝/（59ファイル）
├── 砂防・地すべり対策/（181ファイル）
└── 道路維持・修繕/（411ファイル）
```
---

## 🙌 貢献方法

このリポジトリは **buildingSMART Japan** が管理しており、外部からのコントリビューションは現在受け付けておりません。  
ご意見・ご要望は [buildingSMART Japan のお問い合わせフォーム](https://www.building-smart.or.jp/library/contact.html) よりご連絡ください。

---

## 📄 ライセンス

本データは **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)** ライセンスの下で公開されています。

- **表示**：出典を明記してください  
- **非営利**：商用利用は禁止されています  
- **継承**：派生物も同じライセンスで公開してください

---

## 🔗 参照リンク

- 📘 [Information Delivery Specification - buildingSMART International](https://www.buildingsmart.org/standards/bsi-standards/information-delivery-specification-ids/)  
- 🏛️ [国土交通省 BIM/CIMポータル](https://www.nilim.go.jp/lab/qbg/bimcim/bimcimindex.html)  
- 🧩 [IDS GitHubリファレンス（英語）](https://github.com/buildingSMART/IDS)  

---

📢 ご質問・ご相談は buildingSMART Japan までお気軽にお問合せください。
