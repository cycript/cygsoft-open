# Physical Memory Read-Only Web Radar for Valorant

This was a project for learning Rust back when I was in school, so no judging please.

I've decided to post it here as I've had no use for it for a really long time and perhaps it could help other people.

Although, the frontend code is absolutely abysmal. The frontend should never be used as-is

[Valorant Api](https://valorant-api.com/) is used for several downloads and data updates
# Features: 
- Auto Updates for new agents (Valorant Api)
- Auto Updates for new maps (Valorant Api)
- - -
- Minimal use of WinApi
- Gets Windows kernel with no api calls
- Enumerate processes without api calls
- Get big pool table  without api calls 
- Read Process memory without api calls (ofc)

if i recall correctly, all these things were achieved using just reading physical memory.


It previously used to Get Big Pool Table to get Vanguard's "Shadow Memory" or "Guarded Memory" pool,
but I think its currently broken (the big pool table parser).
And Vanguard has updated for that to not be of use anymore.

It was only tested on Windows 10 22h2 and was barely ever used.
