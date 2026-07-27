# Commands and permissions

## Commands

| Command | Description | Permission | Usage |
|---------|-------------|------------|-------|
| `/loan` | Borrow, view, or repay a personal loan | `` | `/<command> <take/info/repay/list> [amount]` |
| `/townloan` | Mayor â€” borrow from Server Reserve into town bank, or repay | `` | `/<command> <take/repay/info/list> [amount]` |
| `/rootloans` | Admin reload for Root-Loans | `rootloans.reload` | `/<command> reload` |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `rootloans.use` | Use /loan take, info, and repay | `true` |
| `rootloans.town.use` | Mayor use /townloan take, repay, and info | `true` |
| `rootloans.list` | View all active personal loans | `op` |
| `rootloans.town.list` | View all active town loans | `op` |
| `rootloans.reload` | Reload root-loans.yml | `op` |

