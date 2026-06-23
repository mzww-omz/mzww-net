<script>
    import Web from "$lib/web.svelte";
    import Logo from "$lib/Logo.svelte";
    import QR from "$lib/assets/qr.png";
</script>

<div class="bgh">
    <main class="mx-auto max-w-2xl px-2">
        <a aria-label="mzww.net" href="/"><h1 class="text-5xl md:text-7xl">mzww.net</h1></a>
        <h2 class="text-2xl md:text-4xl text-stone-500">MZWW / tech enthusiast<br>I can speak English / Japanese</h2>

        <div class="text-xl md:text-2xl">
            Java / Python / JavaScript / Svelte
        </div>
        <div class="text-2xl my-5">
            Hello, welcome to my website. <br>
            Contact me with Twitter!
        </div>
        <div class="links my-5 mzlink">
            $ cat links.txt<br>
            <Web linkColor="#000000" linkUrl="https://mzww.fanbox.cc/" linkText="Donate me" />
            <Web linkColor="#1D9BF0" linkUrl="https://x.com/mzwwnet" linkText="Twitter" />
            <Web linkColor="#FF0033" linkUrl="https://youtube.com/@mzwwnet" linkText="YouTube" />
            <Web linkColor="#101411" linkUrl="https://github.com/mzww-omz" linkText="Github" />
            <Web linkColor="#FF5700" linkUrl="https://www.reddit.com/user/mzww_omz/" linkText="Reddit" />
            <Web linkColor="#252525" linkUrl="https://www.nicovideo.jp/user/126429574" linkText="NicoNico" />
            <Web linkColor="#9146FF" linkUrl="https://www.twitch.tv/mzwwnet" linkText="Twitch" />
            <Web linkColor="#9CC500" linkUrl="https://misskey.io/@mzwwnet" linkText="Misskey.io" />
            <Web linkColor="#000000" linkUrl="https://nostter.app/nprofile1qqsvp2ccyy20swa8vc447ct2ng6eer2p4xgupcl0rd706uurm3rtfyqnqr0s5" linkText="Nostr" />
            <Web linkColor="#B90000" linkUrl="https://www.last.fm/user/mzww" linkText="Last.fm" />
            <Web linkColor="#41C9B4" linkUrl="https://note.com/mzww_" linkText="note" />
            <Web linkColor="#35465C" linkUrl="https://www.tumblr.com/mzwwnet" linkText="Tumblr" />
            <Web linkColor="#F7A028" linkUrl="https://scratch.mit.edu/users/mzww-omz/" linkText="Scratch" />
            <Web linkColor="#42E661" linkUrl="https://linktr.ee/mzww" linkText="Linktree" />
            <Web linkColor="#1185FE" linkUrl="https://bsky.app/profile/mzwwnet.bsky.social" linkText="Bluesky" />
            <Web linkColor="#FF3300" linkUrl="https://soundcloud.com/mzww" linkText="SoundCloud" />
            <Web linkColor="#5865F2" linkUrl="https://discord.gg/bmw2p5sCmW" linkText="Discord" />
            <Web linkColor="#0DBD8B" linkUrl="https://matrix.to/#/#mzww-p:matrix.org" linkText="Matrix" />
            <Web linkColor="#00D2F3" linkUrl="https://dailymotion.com/user/mzww" linkText="Dailymotion" />
            <Web linkColor="#FC6D26" linkUrl="https://gitlab.com/mzww" linkText="GitLab" />
            <Web linkColor="#FF66AA" linkUrl="https://osu.ppy.sh/users/37776877" linkText="osu!" />
            <Web linkColor="#0096FA" linkUrl="https://www.pixiv.net/users/127213384" linkText="Pixiv" />
        </div>
        <div class="links my-5 mzlink">
            $ cat products.txt<br>
            <Web linkColor="var(--color-rose-500)" linkUrl="https://yuri.red/" linkText="yuri.red" />
        </div>
        <div class="flex flex-wrap items-center justify-center">
            <img src={QR} alt="QR code of this website" />
            <div class="basis-full"></div>
            <h2 class="text-xl text-stone-400 my-7">Copyright 2026, MZWW</h2>
        </div>
    </main>
</div>

<style>
    main {
        font-family:
            -apple-system,
            BlinkMacSystemFont,
            "Segoe UI",
            "Hiragino Sans",
            "Hiragino Kaku Gothic ProN",
            "Yu Gothic UI",
            "Yu Gothic",
            "Meiryo",
            "Noto Sans JP",
            sans-serif;
    }
    .bgh {
        background-size: 15px 15px; /* マスの大きさ */
        background-image:
            linear-gradient(to right, #e0dcd3 1px, transparent 1px),
            linear-gradient(to bottom, #e0dcd3 1px, transparent 1px);
        background-color: #ffffff; /* ベースの背景色 */
        min-height: 100dvh;
    }
    
</style>