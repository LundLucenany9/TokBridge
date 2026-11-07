# TokBridge (Out of date)

TokBridge adds [TikTok](https://tiktok.com/) LIVE chat to Minecraft. It can also display the profile (including the name and profile picture) of viewers on screen. The profile picture can be displayed as block art in your Minecraft world.

## Configuration:
### Client Settings:
- **Profile Position**: The position of the viewer's profile on the HUD. Can be disabled.
- **Margin**: The margin from the screen edge.
- **Display User Profile Picture**: Enables/disables displaying the profile picture on the HUD.
- **Picture Size**: The size of the profile picture in pixels.
- **Username Position**: The position of the username relative to the profile picture.
- **Gap**: The gap between the profile picture and username.

### Server Settings:
- **Username**: The username of the target TikTok streamer.
- **Display TikTok Chat in Minecraft**: Enables/disables TikTok chat in Minecraft.
- **Update Rule**: Determines which TikTok LIVE events update the viewer's profile and block art (Follows, Subscriptions, Gifts, Shares, Joins, Comments, and Likes).
- **Enable Block Placing**: Enables block art. (Will only work if a target destination is defined.)
- **Block Art Size**: The size of the block art. The picture will be retrieved at 72×72 pixels. Upscaling will blur the edges but provides better color accuracy.

## Usage
1. Set up your config.
2. Go LIVE before joining a world or starting the server. Alternatively, you can use /connect after joining a world or starting the server.
3. To optionally enable block art, obtain the **Image Item** from the Operator Utilities tab. This tab can be enabled under *Options → Controls* in Minecraft's settings.
4. Click the block that should serve as the bottom-left corner of the block art. An indicator will be shown.

## Commands
- `/connect`: Connects or reconnects to TikTok LIVE.
- `/disconnect`: Disconnects from TikTok LIVE.
