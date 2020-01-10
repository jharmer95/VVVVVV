# Goals for fork

By forking this project, I have a few ideas on how to improve this game. For now, I am focusing on the desktop version:

- Analyze with tools like cppcheck, clang-tidy, ReSharper, etc.
  - Find critical bugs, warnings, potential optimizations, etc.
- Stabalize game to allow for release builds
  - Currently, per the original dev, you can only build in debug otherwise the game freaks out, this should be fixed in the code
- Move from tinyxml to rapidxml
  - rapidxml is faster and more efficient than tinyxml
