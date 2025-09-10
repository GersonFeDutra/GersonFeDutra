# Hello World!

<div imgs align="right">

𝓖𝓪𝓶𝓮 𝓓𝓮𝓿 𝓲𝓼 𝓶𝔂 𝓹𝓪𝓼𝓼𝓲𝓸𝓷
[<img src="assets/icons/social_media/font-awesome/itch-io.png" width="46pt" />](https://gersonfedutra.itch.io/)
[<img src="assets/icons/social_media/font-awesome/linkedin.png" width="46pt" />](https://linkedin.com/in/gersonfedutra)
[<img src="assets/icons/social_media/font-awesome/instagram.png" width="46pt" />](https://instagram.com/gersonfedutra/)
[<img src="assets/icons/social_media/threads.png" width="36pt" />](https://www.threads.net/@gersonfedutra)

</div>

<!-- [<img src="assets/icons/FontAwesome/social_media/twitter.png" width="46pt" />](https://twitter.com/GersonFeDutra) -->

<div topics>

<img src="assets/lvl1_link.gif" align="right" >

- ⭐ Favorites:
    - Languages: **[C/C++](https://en.cppreference.com/w/cpp)**, **[Gdscript](https://docs.godotengine.org/en/latest/tutorials/scripting/gdscript/index.html)**, [**Python** <img src="assets/icons/techs/languages/python.png" width=20pt />](https://www.python.org/) & **[Go <img src="assets/icons/techs/languages/Go/Go-Logo_White.svg" width=20pt>](https://go.dev/)**
    - Topics: `Software Engineering`, `Game Development`, `Godot 2D`, `Teaching`
- 📖 Currently learning:
    - `Computer Graphics`: `Open GL`
    - `Unreal Engine` **`C++`** `3D Game Development`
    <!-- - `Automatae` & `Formal Languages` -->
    <!-- - Blender & Unreal Engine -->
    <!-- - Calculus & Statistics -->
    <!-- - Calculus & Physics -->
    <!-- - Typescript & Flutter -->
- 🧐 Interests:
    - `Computer Graphics` & `Shaders`
    - `Game Design`, `Graphics Design`, `Software Design`
    - `Procedural Generation` & `Game AI`
    <!-- - `Algorithms Design` -->
- 💙 [<img src="assets/icons/techs/Godot/godot.png" width=20pt> **Godot**](https://godotengine.org/)
    - Enthusiast since 2016

</div>


### Tools
---

<div id="tools">

[<img src="assets/icons/techs/Git/git.svg" width=24pt>](https://git-scm.com/) &emsp;
[<img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/github.svg" width=24pt/>](https://docs.github.com/) &emsp;
[<img src="https://raw.githubusercontent.com/garrett/Tux/main/tux.svg" width=24pt/>](https://www.linux.org/) &emsp;
[<img src="assets/icons/techs/Arch/arch-logo.png" width=29pt>](https://archlinux.org/) &emsp;
[<img src="https://raw.githubusercontent.com/odb/official-bash-logo/master/assets/Logos/Icons/SVG/16x16.svg" width=24pt/>](https://www.gnu.org/software/bash/) &emsp;
[<img src="https://www.vim.org/images/vim_small.gif" width=20pt/>](https://www.vim.org/) &emsp;
[<img src="assets/icons/techs/NeoVim/neovim-icon.svg" width=20pt>](https://neovim.io/) &emsp;
[<img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" width=24pt>](https://code.visualstudio.com/) &emsp;
[<img src="./assets/icons/techs/languages/C/c-programming.svg" width=24pt>](https://www.amazon.com/dp/0131103628) &emsp;
[<img src="./assets/icons/techs/languages/C/CPlusPlus.svg" width=24pt>](https://en.cppreference.com/w/cpp) &emsp;
[<img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg" width=24pt>](https://www.python.org/) &emsp;
[<img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg" width=24pt>](https://www.microsoft.com/pt-br/microsoft-365/excel) 
<!--<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Toolbaricon_RegEx.svg/1920px-Toolbaricon_RegEx.svg.png" width=65pt>-->

</div>

---

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GersonFeDutra&layout=compact&theme=synthwave&hide_border=true&langs_count=8&hide=jupyter%20notebook,html,cmake" align="right" alt="Top Languages" >

```Cpp
#include <print>

#if defined(__unix__) || defined(__linux__)
    // Ansi escape by default!
    
    /* Same as std::print */
    template <typename... T>
    inline void print(const char* string, T... args) {
        std::print(string, args...); // re-direct to STL implementation.
    }
#elif defined(_WIN32) || defined(_WIN64)
    // here: <https://gist.github.com/GersonFeDutra/e2828efcb5d2e7c871c4ac1e239b60fe#file-windows_ansi_fallback-hpp>
    #include <windows_ansi_fallback.hpp>
#endif

int main()
{
    print("\033[32m" "Hello World!" "\033[m\n");
}
```
