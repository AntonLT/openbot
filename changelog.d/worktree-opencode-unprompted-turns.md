### Fixed

- An OpenCode agent's answer after a background subagent ends now shows in the chat. Before, OpenCode saved the answer, but the chat never showed it, because no message had started that turn.
- Text that an OpenCode or other ACP agent writes before it uses a tool now shows as a message, with the steps of the turn between its messages. Before, the text was hidden in the steps, and the text of two steps could show as one line.
