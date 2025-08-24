![simp chat](https://github.com/zfex77/simplechat/assets/139940269/b7e5ccc1-6466-4b00-a137-90c671babb06)
***
A chatting application that uses the PubNub API. Part of the [SimpleHTMLs](https://github.com/zfex77/simplehtmls) project.

> ⚠️ This application uses a free PubNub account which allows up to 1,000,000 "transactions" per month. What this means is that every time a user sends a message, receives a message, or loads message history, a transaction will be expended.

> **Before using this platform,** please read the [Terms of Service](https://github.com/zfex77/simplechat/blob/main/docs/tos.md).

## Features
- Real-time messaging
    - Seven day message history
    - Timestamps
-  Channels
    - Users can select and switch between channels seamlessly
    - User can create channels with custom names
    - Channels can be shared via a link
    - Channels are private and can only be accessed by link
- Media
    - YouTube Videos
    - Vimeo Videos
    - Images (jpg, png, gif, webp, svg, bmp, etc.)
    - Direct Video Files (mp4, webm, etc.)
    - Direct Audio Files (mp3, wav, etc.)
    - HTML Embeds (slideshows, twitter posts, PDFs, etc.) 
        - Handles HTML embeds to ensure security and safety
- Light and dark modes


## How does it work?
- To send messages, you can use the send button or press the enter key. 
-  To create private channels, use the "+" button to create a channel, and use the "📤" button to share the link to others.
- Because of how  PubNub works, we **do not support image sharing**, however it is still possible to send all kinds of media over SimpleChat. To send images, copy the direct image link, (i.e., https://example.com/example.png) and paste it in chat and it will visible to all users in the channel. This method works for all image files.
- To embed other types of media such as videos, sending a YouTube video link will directly embed it in that message. For things like powerpoints, twitter posts, PDFs, and etc., using the embed code and pasting it into chat will display it in chat.
