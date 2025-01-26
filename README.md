

<!--
**Arniiiii/Arniiiii** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Who am I
just a guy from Ukraine that knows some C++, Python and CMake.

## My public activity
1. Writing ebuilds for Portage package manager. Check [ex_repo](https://github.com/Arniiiii/ex_repo)
2. Helping some random guys at C++ and Gentoo discord channels
3. Reporting bugs to [bugs.gentoo.org](https://bugs.gentoo.org/buglist.cgi?email2=lg3dx6fd%40gmail.com&emailassigned_to2=1&emailcc2=1&emaillongdesc2=1&emailreporter2=1&emailtype2=substring&order=changeddate%20DESC%2Cpriority%2Cbug_severity&query_format=advanced&resolution=---&resolution=FIXED&resolution=INVALID&resolution=WONTFIX&resolution=LATER&resolution=REMIND&resolution=DUPLICATE&resolution=WORKSFORME&resolution=CANTFIX&resolution=NEEDINFO&resolution=TEST-REQUEST&resolution=UPSTREAM&resolution=OBSOLETE&resolution=PKGREMOVED)
4. Making some projects easy to add and use with CMake via `add_subdirectory` or [CPM](https://github.com/cpm-cmake/CPM.cmake) ([+] - separate project, [-] - not merged upstream, [x] - merged, [ ] failed for a reason) :
    - [+] [Boost](https://github.com/Arniiiii/AddBoost.cmake) , a big known library for C++
    - [-] [certify](https://github.com/Arniiiii/certify_cmake) , a library for finding local certificates on some systems. Useful for Boost.Asio and Boost.Beast for SSL connections.
    - [+] [simdjson](https://github.com/Arniiiii/simdjson_use_release) . I've made a simple script to ensure that you are using simdjson how it is expected by simdjson's developers. No finding local simdjson though.
    - [-] [csv-parser](https://github.com/Arniiiii/csv-parser) . It's installable now.
    - [x] [boost/ut](https://github.com/Arniiiii/ut_cmake_fix).  Fixed some issues with cmake and gh workflows
    - [ ] [constexpr-to-string](https://github.com/Arniiiii/constexpr-to-string-cmake). It's usable now. Not merged since someone dislikes CMake's configure-time dependencies.
    - [ ] [fast_io](https://github.com/Arniiiii/fast_io_cmake_cpm) . I've tried to make a pull request with this and they discouraged that. :( . Though, around 30% of tests, examples, benchmarks and fuzzers are incompilable since the developers don't care about those ...
    - [-] [libWRP](https://github.com/Arniiiii/libWRP-key-cmaked-n-updated) . It's a library that allows emulating keyboard output on Windows, Linux and MacOS.
    - [x] [magic_enum](https://github.com/Arniiiii/magic_enum_cmake_fix) . Fixed installing and some other problems
    - [-] [fmtlog](https://github.com/Arniiiii/fmtlog_cmake_fix) . It's a logging library. You can use, though, it has unknown problem for Windows (it hangs 1 test) and it has about 327 warnings, since it was written in C-style and uses `reinterpret_cast`-like  C-style `(smth *)` casting to access private variables.
    - [ ] baresip's cmake better support didn't finish.
5.  Making some shitty projects either for:
    - [x] university
    - [x] as a test "job" for a job
6. Customizing my [neovim config](https://github.com/Arniiiii/Nvchad_config_cpp)

