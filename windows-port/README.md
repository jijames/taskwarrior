Native Windows (MSVC) port of Taskwarrior 3.5.0 (upstream 3419d5b).

The in-tree changes are committed directly. One change lives in the libshared submodule, which a commit here cannot carry.
After checking out with submodules, apply it from the repo root:

    git apply windows-port/libshared-FS.patch
