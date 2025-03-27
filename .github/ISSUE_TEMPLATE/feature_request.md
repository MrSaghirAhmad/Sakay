---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: bug, documentation, duplicate, enhancement, good first issue, help wanted
assignees: MrSaghirAhmad

---

**Is your feature request related to a problem? Please describe. **
"Yes, the feature request is related to the problem of large media file sharing and performance issues in messaging apps. Currently, many popular messaging apps, including WhatsApp, have difficulties handling large video and media files efficiently. These apps often experience slow upload/download speeds, lagging during playback, and excessive data usage, especially for users with slow internet connections or limited storage on their devices. Users who want to send high-quality videos or media files face delays or quality loss due to compression or file size limitations. Additionally, many apps become heavy and resource-intensive, leading to poor performance on lower-end devices."


**Describe the solution you'd like**
"I would like Sakay App to implement a lightweight and efficient media-sharing feature that supports videos, images, and other media files. The app should allow users to send large files such as videos without facing performance issues or lag. Additionally, the solution should include:
Efficient Compression: Automatically compress media files to reduce data usage while maintaining a high level of quality.
Progressive File Upload: Allow users to upload and send videos in chunks, which would minimize delay and provide a smoother experience.
Fast Playback: Videos should load and play instantly without buffering, even in low-bandwidth environments.
Background Media Processing: The app should handle media processing in the background, allowing users to continue using the app without interruptions.
Minimal Resource Usage: The app should remain lightweight, using minimal storage and battery power during media uploads, downloads, and playback."

**Describe alternatives you've considered**

Using Compressed Media:
I considered implementing a feature where media files like videos are automatically compressed before sending to reduce data usage and improve speed. However, compression often results in lower quality, which is not ideal for users who want to send high-quality videos.

Cloud Storage Integration:
Another alternative is to integrate cloud storage solutions like Google Drive or Dropbox to handle large video uploads and shares. This could alleviate storage and performance issues on the app itself. However, this solution could potentially increase app complexity, and users might face issues with data privacy or dependency on an internet connection.

File Size Limitation:
I thought about introducing a file size limitation for video uploads to keep things simple and prevent lag. However, this would restrict users who want to share high-quality or longer videos, which is not an ideal user experience for a video-centric app.

Peer-to-Peer File Sharing (P2P):
Implementing P2P sharing could reduce server load and speed up file transfers. However, P2P might not work effectively in all network environments, especially if users are behind strict firewalls or NATs (Network Address Translators), and it may require additional infrastructure for secure and reliable transfers.


**Additional context**
Target Audience: The primary users of Sakay will be those seeking a lightweight, fast, and feature-rich messaging platform that supports high-quality media sharing (especially videos). This includes users in regions with limited internet speed or those looking for an alternative to heavier apps like WhatsApp.

App Requirements:
The app should run smoothly on lower-end devices and use minimal resources like CPU, RAM, and storage.
A focus on security is crucial. End-to-end encryption will be implemented to ensure user privacy while sharing media.
The app will support multimedia messaging (text, voice, video, and images) with support for group chats.

Challenges:
Balancing performance and media quality, particularly with video files, is one of the key challenges. Ensuring that videos are fast to upload and share without compromising on the quality of content.
Network performance, especially in areas with slow internet connections, is a consideration for optimizing media uploads, downloads, and video streaming.

Long-Term Vision:
Over time, Sakay will expand to include features like video calls, voice messages, and integrated media editing tools to enhance user interaction.
