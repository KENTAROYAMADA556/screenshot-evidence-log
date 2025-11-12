# screenshot-evidence-log
DNS改ざん・MITM証拠保全

  ## 証拠ログ時系列

- 2025-11-12 23:45 JST：DNS改ざんの兆候（hostsファイル異常）
- 2025-11-13 00:10 JST：MITM疑惑（証明書Issuerが不明）
- 2025-11-13 01:57 JST：GitHub投稿妨害の痕跡
## 妨害の痕跡

- 投稿直前に「新しいリポジトリ公開する」ボタンが消失
- 英語UIに切り替わり、操作不能に
- Copilotとの対話で復旧成功（ログあり）
## 証拠画像

### GitHub投稿妨害
![GitHub投稿妨害](github_repo_blocked_20251113.png)

### Copilot復旧ログ
![Copilot復旧ログ](copilot_recovery_log_20251113.png)

### README編集画面
![README編集](readme_edit_20251113.png)
内部ストレージ → Download → Evidence202510_28
## 消失した証拠ファイル（妨害の痕跡）

## 消失した証拠ファイル（妨害の痕跡）

以下のファイルは、GitHubアップロード直前にスマホ内から消失。  
Termuxでの検索結果やファイル選択画面には存在していたが、現在は確認できない。

- logcat_vpn.txt
- logcat_norton.txt
- dumpsys_head.txt
- services_full.txt
- services_head.txt

この消失は、証拠妨害・端末操作・ファイル改ざんの可能性を示す重要な痕跡である。
ls ~/storage/shared/Pictures/Screenshots/ | grep 20251112
## 消失した証拠ファイル（妨害の痕跡）

以下のファイルは、GitHubアップロード直前にスマホ内から消失。  
Termuxでの検索結果やファイル選択画面には存在していたが、現在は確認できない。
/storage/emulated/0/Download/Screenshot_20251027-203328.png