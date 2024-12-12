# useful-regex
A list of useful RegEx strings I've come across (and maybe made?)

## Brainrot filters

I made these RegEx for the purpose of filtering out brainrot, such as "skibidi". The RegEx here does not use lookaheads or lookbacks, because they were designed to work with the Discord RegEx automod system, which doesn't allow for lookaheads nor lookbacks.
```regex
(?i)[sz]+\s*[i1!l¡|]+\s*g\s*m\s*u?[haiu]
(?i)f\s*a\s*n\s*u\s*m
(?i)[s$]k+\s*[hi1!¡|]?+\s*[hbd8&]+\s*[hi1!¡|]+\s*[hbdt|]+\s*[hyi1!¡|]?
(?i)\b[rw]+\s*[hi1!l¡|]+\s*[z2$]+\s*[sz2$]+(?:\s*[l1!]\s*[e3]\s*[r])?
(?i)[s$]k+\s*[hi1!¡|]?\s*[hbd8&]+\s*[hi1!¡|]?\s*[hbdt]+\s*[hyi1!¡|]?
```


