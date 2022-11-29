# Readme

![visitor badge](https://visitor-badge.glitch.me/badge?page_id=mrtejas99.visitor-badge&left_text=Visitors)
[![Ruby](https://badgen.net/badge/icon/ruby?icon=ruby&label)](https://https://ruby-lang.org/)




**Step 1:** Download and install a Ruby+Devkit version from [RubyInstaller Downloads](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-3.1.2-1/rubyinstaller-devkit-3.1.2-1-x64.exe). Use default options for installation.

**Step 2:** Run the `ridk install` step on the last stage of the installation wizard. This is needed for installing gems with native extensions.

**Step 3:** Open a new command prompt window from the start menu, so that changes to the `PATH` environment variable becomes effective. 

**Step 4:** Install Jekyll and Bundler using `gem install jekyll bundler`

**Step 5:** Check if Jekyll has been installed properly: Type `jekyll -v` in terminal

 ![jekyll version](/img/jekyll_version.png)

**Step 6:** Create a new blog with the `jekyll new myblog` command

 ![jekyll install](/img/jekyll_install.png)

**Step 7:** From the `myblog` folder created in the previous step issue the following command
```bash
cd myblog
bundle exec jekyll serve
```
 ![jekyll exec](/img/jekyll_exec.png)


**Step 8:** Open a browser to http://localhost:4000 and view your Jekyll blog on Windows

 ![jekyll ui](/img/jekyll_ui.png)
