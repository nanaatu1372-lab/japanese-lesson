#!/bin/bash
# GitHubのindex.htmlから名前を削除するスクリプト
# 使い方: index.htmlと同じフォルダで bash remove_name.sh を実行

FILE="index.html"

if [ ! -f "$FILE" ]; then
  echo "エラー: index.html が見つかりません"
  exit 1
fi

# バックアップ
cp "$FILE" "${FILE}.backup"
echo "✓ バックアップ作成: ${FILE}.backup"

# 名前の削除・置換
sed -i 's/監修 垰田直美　日本語講師/日本語講師/g' "$FILE"
sed -i 's/監修：垰田直美　日本語講師/日本語講師/g' "$FILE"
sed -i 's/監修：垰田直美/日本語講師/g' "$FILE"
sed -i 's/垰田直美　日本語講師/日本語講師/g' "$FILE"
sed -i 's/垰田 直美/—/g' "$FILE"
sed -i 's/垰田直美/—/g' "$FILE"
sed -i 's/講師（垰田先生）が厚労省への申請が必要です/講師が厚労省への申請が必要です/g' "$FILE"
sed -i 's/垰田先生/講師/g' "$FILE"

echo "✓ 名前の削除完了"
echo ""
echo "残っている「垰田」の確認:"
grep -n "垰田" "$FILE" && echo "→ まだ残っています" || echo "→ 完全に削除されました ✓"
