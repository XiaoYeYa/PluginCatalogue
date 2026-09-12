**English** | [中文](readme-zh_cn.md)

\>\>\> [Back to index](/readme.md)

## online_player_api

### Basic Information

- Plugin ID: `online_player_api`
- Version: *Data fetching failed*
- Total downloads: N/A
- Authors: [Andy Zhang](https://github.com/AnzhiZhang)
- Repository: https://github.com/AnzhiZhang/MCDReforgedPlugins
- Repository plugin page: https://github.com/AnzhiZhang/MCDReforgedPlugins/tree/master/src/online_player_api
- Labels: [`API`](/labels/api/readme.md)
- Description: *Data fetching failed*

### Dependencies

*Data fetching failed*

### Requirements

*Data fetching failed*

### Introduction

# OnlinePlayerAPI

> 在线玩家 API

## API

### is_online(player: str, case_sensitive: bool = True)

如果玩家在线, 返回 `True`。

如果玩家不在线, 返回 `False`。

`case_sensitive` 是否忽略大小写。

### check_online(player: str, case_sensitive: bool = True)

与 `is_online(player)` 相同。

### get_player_list()

返回所有在线玩家的列表。

### normalize_player_name(player: str)

返回给定玩家名称的正确大小写形式。

如果玩家不在线，则引发 ValueError。

### Download

> [!IMPORTANT]
> Read the README file in plugin repository before using it.

*Data fetching failed*

