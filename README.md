# Roblox Blocklist for Pi-hole

This is a ready-made blocklist for [Pi-hole](https://pi-hole.net/) designed to block access to Roblox on all devices in your home network.  
It works by blocking the main domains used by Roblox games, apps, and website.

## What is this for?

If you want to stop devices on your network from accessing Roblox (for example, for parental control), you can use this list with your Pi-hole installation.  
It’s easy to use and you don’t need to be a technical expert.

## How do I use this blocklist?

1. **Copy the Raw Link:**
   - Click on the `roblox-adlist.txt` file in this repository.
   - Click the **Raw** button.
   - Copy the link from your browser’s address bar.

2. **Add the List to Pi-hole:**
   - Open your Pi-hole web interface.
   - Go to **Group Management** > **Adlists**.
   - Paste the link you copied into the **Address** box.
   - Click **Add**.

3. **Update Pi-hole:**
   - In the Pi-hole web interface, click **Update Gravity** (or run `pihole -g` in the terminal).
   - This applies the new blocklist.

4. **You’re Done!**
   - Roblox should now be blocked on all devices using your network’s Pi-hole.

## What does this block?

This list includes the main domains used by Roblox for:
- The website
- Game servers
- Content delivery (CDN)
- APIs and services

It is designed to block Roblox games and access to the Roblox website as completely as possible.

## Can I unblock Roblox later?

Yes.  
Just remove this adlist from Pi-hole’s **Adlists** section and update gravity again.  
Roblox access will be restored.

## Who maintains this list?

This list is maintained by the community.  
If you find a Roblox domain that isn’t blocked, or if you have suggestions, please open an issue or submit a pull request.

---
