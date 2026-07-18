# Webring
List of participating club members for the LUGVITC and [VIT Webring](https://webring-vit.vercel.app). The format is following [theirs](https://github.com/backdoors-org/webring/blob/main/members.json).

Add your blog, portfolio, or personal projects/experiments display website here, show off and brag!

# How to join
Fork this repository and add your own entry to the end of [members.json](./members.json), keeping all the other entries and format intact. Then file a pull request to this repository, asking to be added.

To make your website link to other websites automatically, [follow this guide:](https://github.com/backdoors-org/webring#how-to-add-prev--next--random-to-your-site) You need to prepare your website with this before you are added to the webring.

# Format:
```json
{
  "id": "A unique ID for your website",
  "name": "Preferred display name",
  "url": "Your personal website's root URL. Add the webring widget anywhere on your site in order for it to participate",
  "git_acc": "Your github, codeberg, forgejo profile link. This will give you an avatar image",
  "batch": "<Which vit campus you are from> <Your course code> <starting year>-<ending year>",
  "desc": "Add any description of your website or interests here"
},
```
Make sure all your links have `https://` at the beginning or else it won't work.

Your chosen `id` will identify your website everywhere.

<details><summary>Example</summary>
<p>

```json
{
  "id": "derpitron",
  "name": "Derpitron",
  "url": "https://5rupee.co.in",
  "git_acc": "https://codeberg.org/derpitron",
  "batch": "vitc ecm 24-28",
  "desc": "Calligraphy, dogs, weird systems"
},
```

Follow this format exactly
</p>
</details> 

# Privacy Notes
This info is public, and syndicated to (shared with) [webring-vit.vercel.app](https://webring-vit.vercel.app). So other VIT webring websites, people using RSS feeds/crawlbots, or the Internet Archive, etc. may automatically copy these details any time, without your knowledge. If you're concerned about privacy doxxing osint or whatever take this into mind. Join the webring and add your details here **only if you're fine with that**.
