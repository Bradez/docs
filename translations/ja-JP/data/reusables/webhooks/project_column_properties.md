| キー                    | 種類        | 説明                                                                       |
| --------------------- | --------- | ------------------------------------------------------------------------ |
| `action`              | `string`  | プロジェクト列で実行されたアクション。 `created`、`edited`、`moved`、`deleted`のいずれか。           |
| `changes`             | `オブジェクト`  | アクションが`edited`だった場合、プロジェクト列に対する変更。                                       |
| `changes[name][from]` | `string`  | アクションが`edited`だった場合、以前のバージョンの名前。                                         |
| `after_id`            | `integer` | アクションが"moved"だった場合、この列がフォローするようになった列のid。 これがプロジェクト内の最初の列だった場合は`null`になる。 |
| `project_column`      | `オブジェクト`  | [プロジェクトの列](/rest/reference/projects#columns)自体。                          |
