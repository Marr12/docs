{% note %}

**ノート:** Checks APIは、チェックスイートもしくはチェック実行が作成されたリポジトリ内のプッシュのみを探します。 フォークされたリポジトリ内のブランチへのプッシュは検出されず、空の`pull_requests`配列と、`head_branch`に`null`値が返されます。

{% endnote %}
