Fixed error
```
error Invalid regular expression: /(.*\\__fixtures__\\.*|node_modules[\\\]react[\\\]dist[\\\].*|website\\node_modules\\.*|heapCapture\\bundle\.js|.*\\__tests__\\.*)$/: Unterminated character class.
```
In `\node_modules\metro-config\src\defaults\blacklist.js` variable `sharedBlacklist`.

Thanks to the issue comment from [expo-cli](https://github.com/expo/expo-cli/issues/1074#issuecomment-546167583) repository.
