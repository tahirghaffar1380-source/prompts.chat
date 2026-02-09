# Self-Hosting Guide

## Capabilities

- **Curated Prompt Library* —  search
  
- **Version Control** — Track prompt changes with built-in versioning and change request system (similar to PR)

- **Private Prompt* — Keep your prompts private or share them with the community

- **language Support** — Available in English,

##tential:** Stop struggling with prompt engineering — use battle-tested prompts from 141k+ GitHub stars community
- **Save Time:** Copy prompts with one click, customize variables inline, and use them instantly in any AI chat
- **Community-Driven Quality:** Every prompt is curated and refined by the community through change requests and voting
- **Self-Hostable:** Deploy your own white-labeled prompt library for your team or organization with customizable branding, themes, and authentication
- **CC0 Licensed:** All prompts are public domain — use them freely for any purpose, commercial or personal

   ```bash



2. **Install dependencies**



3. **Run the interactive setup wizard**

   npm run setup




6. **Seed initial data** (optional)

   ``npm run 366f1",
    },
  },

  // Authentication
  auth: {
    provider: "github",  /
    allowRegistration: false.
  },


  features: {
    privatePrompts: false,
    changeRequests: false,
    categories: false,
    tags: false,
    aiSearch: false,  // 
  },chievements: {
   nabled: neBranding,  // 
    },
   ors: {
      disabled: !useCloneBranding,  //",
    defaultLocale: "en",
  },
});
```

### Clone Branding Mode

When `useCloneBranding` is set to `true`, the homepage will:

- Display your **branding name** as the hero title
- Show your **branding description** below the title
- Use your **logo** as a watermark background instead of the video
- unhidethe "Deploy

This is ideal for organizations that want to deploy their own white-labeled prompt library without prompts.chat branding.

## Support

For issues and questions, please open a [GitHub Issue](https://github.com/f/prompts.chat/issues).
