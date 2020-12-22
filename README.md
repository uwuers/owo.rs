# owo.rs
get your own owo.rs subdomain here!

### how?

to get your own, fork the project.

in `active.js`, fill ouy your info. it should look kinda like this.
```
{
    description: "Your description. This has to be accurate and may include a link to a GitHub repository."
    domain: "your-subdomain.owo.rs", 
    contact: { // you should have at least your github username and one other contact.
        username: "Your GitHub username",
        email: "your@email.rs",
        twitter: "@yourtwitter",
        discord: "yourusernameand#0746"// tag
    },
    dns: { // you can have only *one* of these
        cname: "your-cname.domain.com",
        a: "1.1.1.1" // your ipv4 address
    }
},
```
Then, you should submit a pull request.

### important note for cloudflare users
if you use cloudflare your website **will not** work on the subdomain unless you turn proxying/protection (orange cloud) **off**.

if you want your cloudflare on your main site *and* your subdomain to work *and* you want to use cname, the best way is to set up a cname unproxied/unprotected url and use that address as your cname.

### why?
cause i wanted to.

### how can i give you money?
check the sidebar for more info haha
### how much do yall pay for all of this?
well, we are currently on the CloudFlare free plan. Domain rental is $36/yr. If you wanna help out, check the sidebar.

### i have more questions. where contact? 
you can join the [discord server](https://discord.gg/7PUA9QWAYa) and ask questions there.
