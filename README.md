> #### <code>_Getting done everything repetitive that humans don't like. Not only typo clean-ups. You might know something specific from your field, that is as big as your niche is, if we can fix it for everybody._</code>

#### Did you hear about [Wikipedia/MediaWiki Bots?](https://en.wikipedia.org/wiki/Wikipedia:Bots)
 - 2500 such routines are approved there:  [en.wikipedia.org/Category:Approved_Wikipedia_bot_requests_for_approval](https://en.wikipedia.org/wiki/Category:Approved_Wikipedia_bot_requests_for_approval) <br>  + _compare : [**huginn**](https://github.com/huginn/huginn); ([**siteinspector**](https://github.com/siteinspector/siteinspector), [actionsflow](https://github.com/actionsflow/actionsflow), [**stackstorm**](https://exchange.stackstorm.org), [github action for code typos](https://github.com/marketplace/typo-ci),..._ )
      - **WWWWhat about a Bots also making Pull requests in global Open-Source project?💡💡**
      - **Goal / Milestone NR.1 :**  
          - **Quantity:** > 1 million automatic pull requests // worth >100,000 working hours.  **Claim: Reaching this goal will be very efficient! 😱** spending only < 3000 hours here. Or < 3% (_Efficiency could raise donations against hunger etc... Old News: There is Abundance of opportunity. (Only society, that can be bitter... 🤔) (low server costs too. A task worth >$5 often only costs <$0.001 in electricitiy.)_
          - **Quality:** ratio of denied pull requests < 10% & average amount of 👍/❤'s per pull request > 0.5? (initially, before people get used to it)   
     -  Compare: A tool to search for API keys / private keys etc in a repo [Git Hound](https://github.com/tillson/git-hound/tree/master/internal/app) - was awarded $7500 'bug bounty' by GitHub - so assumably this will result in Github notifications already? - vs. [wild-hunt](https://github.com/d1vious/git-wild-hunt#what-checks-get-run-regexesjson) 
     - So you can tell this repo can intersect much with ['awesome Patterns'](https://github.com/code4charity/PATTERNs--The-RegEx-Collector-queries-ontologies-sql-sparql-nosql-structured-unstructured-data)
   
# To-Do
- anything that enhances & fits in line with existing  [.github/workflow](https://docs.github.com/en/actions) routines  
- much of what Wikipedia Bots do everywhere: 
    - simple(non-debatable)  typos, grammar, formating.   
    - Periodic updates of static data (that is intentionally(or practically) marked up though and just waiting). 
- specific errors of readme.md's or other specific files and/or formats. 
- syntax debugging in all file-types, formalities and code languages. 
(- Loss-less compression of machine files.)
- ...
- ...
- **Specific Category Examples:** (from our experience) 
     - **Browser-Extension Manifest v3**:  We can automate some of the work that becomes inevitable to all extension by 2023 (Through some regex) https://github.com/code4charity/Manifest-v3     
     - _the following tiny (almost rare) task alone might has been done a million times in history (by 1000s of people):_ <br>        **Browser-Extension translations**:   Syncing lines from their English language file (_en/messages.json_) to all their other existing languages files. (_specifically  https://((GitHub|BitBucket).com|SoureForge.net|gitlab.io)/\w*/$BrowserExtensionName/_locales/[a-z][a-z][a-zA-Z_]?[A-Z]?[A-Z]?/**messages.json**_ )   ( google wont show all: [inurl:messages.json  site:github.com OR site:bitbucket.com](https://www.google.com/search?q=inurl%3Amessages.json++site%3Agithub.com+OR+site%3Abitbucket.com) )
      - this task wont mean a lot every time. However developers will feel good to see it & start to expect more pull requests.
      - it is likely that all pull requests for this will be merged(=accepted).
      - Explanation: if there is a new item in en.json, then it should always be copied already to all other language files, because if it is not, then the extension will not fall back to the default language: English (as stated in the manifest.json), but it will instead show the internal names from code.
        - imaginable contraindications: <br>_(maybe not yet required to bring denied pull requests to zero/minimum or 1%° (1 in 1000)_ 
           - Same names(labels) (in Code & English messages.json)
           - International labels in Code (emojis / simplified english / ???)
  - Of course the Example above exists only **based on an complicated part of** (Browser-Extension-)**formality.  However it will be faster/easier to build this than the world** (web browsers, www consortiums) improving such a standard (worth it still even if they'd start changing today and it would only run for some years.)
  - **Please add any examples:**
    - **Example 1:**
       - ...
         - ...
    - **Example 2:**
       - ...
    - **Example 3:** 
       - ...
Many examples might already exist as Github Actions.
Later we can sort examples by efficency.
