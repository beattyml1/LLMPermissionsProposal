# LLMPermissionsProposal

## Meta Tags

```html
<meta property="ai:train" value="disallow">
<meta property="ai:lookup:noref" value="disallow">
<meta property="ai:lookup:summarize" value="requireref">
<meta property="ai:lookup:reference" value="allow">
```

## Robots
```
User-Agent: */?purpose=ai:train
Disallow: /copyrighted

User-Agent: */?purpose=ai:lookup:noref
Disallow: /copyrighted
```
