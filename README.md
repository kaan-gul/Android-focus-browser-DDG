# DuckDuckGo Android (with Added Focus Features)

> **Note:** This is a personal fork of the official DuckDuckGo Android repository. A small set of specific features was added to the browser to turn it into a strict personal productivity and focus tool. 

### 🚀 Features Added
* **Focus Session Timer:** An autonomous 2-minute timer starts when the app resumes. Users can set a custom time via a one-time Material Design FAB, after which the app strictly closes itself.
* **Basic Site Blocker:** Intercepts and blocks a predefined list of distracting websites at the network layer (`shouldInterceptRequest`).
* **YouTube Ad-Skipper:** A lightweight JavaScript injection to automatically skip video ads.

---

*(The original DuckDuckGo Android README continues below)*

# DuckDuckGo Android

Welcome to our android application. We are excited to engage the community in development, see [CONTRIBUTING.md](CONTRIBUTING.md).

## We are hiring!
DuckDuckGo is growing fast and we continue to expand our fully distributed team. We embrace diverse perspectives, and seek out passionate, self-motivated people, committed to our shared vision of raising the standard of trust online. If you are a senior software engineer capable in either iOS or Android, visit our [careers](https://duckduckgo.com/hiring/#open) page to find out more about our openings!

## Building the Project
We use git submodules and so when you are checking out the app, you'll need to ensure the submodules are initialized properly. You can use the `--recursive` flag when cloning the project to do this.

    git clone --recursive https://github.com/duckduckgo/android.git

Alternatively, if you already have the project checked out, you can initialize the submodules manually.

    git submodule update --init
    
## Terminology

We have taken steps to update our terminology and remove words with problematic racial connotations, most notably the change to `main` branches, `allow lists`, and `blocklists`. Closed issues or PRs may contain deprecated terminology that should not be used going forward.

## Contribute

Please refer to [contributing](CONTRIBUTING.md).

## Discuss

Contact us at https://duckduckgo.com/feedback if you have feedback, questions or want to chat. You can also use the feedback form embedded within our Mobile App - to do so please navigate to Settings and select "Leave Feedback".

## License
DuckDuckGo android is distributed under the Apache 2.0 [license](LICENSE).