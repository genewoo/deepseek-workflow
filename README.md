# <img src='Workflow/icon.png' width='45' align='center' alt='icon'> DeepSeek Alfred Workflow

DeekSeek V3/R1 integrations

[⤓ Install on the Alfred Gallery _Unavaliable_](https://alfred.app/workflows/alfredapp/deepseek) 

## Setup

1. Create an DeepSeek account and [log in](https://platform.deepseek.com/login?launch).
2. On the [API keys page](https://platform.deepseek.com/api_keys), click `+ Create new secret key`.
3. Name your new secret key and click `Create secret key`.
4. Copy your secret key and add it to the [Workflow’s Configuration](https://www.alfredapp.com/help/workflows/user-configuration/).

## Usage

### DeekSeek Chat

Query DeepSeek V3 via the `ds` keyword, the [Universal Action](https://www.alfredapp.com/help/features/universal-actions/), or the [Fallback Search](https://www.alfredapp.com/help/features/default-results/fallback-searches/).

Query DeepSeek R1 via the `dsr` keyword, the [Universal Action](https://www.alfredapp.com/help/features/universal-actions/).

![Start DeepSeek query](Workflow/images/about/chatgptkeyword.png)

![Querying DeepSeek](Workflow/images/about/chatgpttextview.png)

* <kbd>↩&#xFE0E;</kbd> Ask a new question.
* <kbd>⌘</kbd><kbd>↩&#xFE0E;</kbd> Clear and start new chat.
* <kbd>⌥</kbd><kbd>↩&#xFE0E;</kbd> Copy last answer.
* <kbd>⌃</kbd><kbd>↩&#xFE0E;</kbd> Copy full chat.
* <kbd>⇧</kbd><kbd>↩&#xFE0E;</kbd> Stop generating answer.

#### Chat History

View Chat History with ⌥↩&#xFE0E; in the `ds` keyword. Each result shows the first question as the title and the last as the subtitle.

![Viewing chat histories](Workflow/images/about/chatgpthistory.png)

<kbd>↩&#xFE0E;</kbd> to archive the current chat and load the selected one. Older chats can be trashed with the `Delete` [Universal Action](https://www.alfredapp.com/help/features/universal-actions/). Select multiple chats with the [File Buffer](https://www.alfredapp.com/help/features/file-search/#file-buffer).