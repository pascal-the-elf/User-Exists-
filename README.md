# User Exists?
Check Username API

## Support Sites
1. Facebook
2. Instagram
3. Github

## API Endpoint

```
https://ue.pascaltheelf.tk/
```

## Usage

Request:
```
https://ue.pascaltheelf.tk/{KEYWORD}/{USERNAME}
```

Success Response:
```javascript
{
  "exists": true || false
}
```

Error Response:
```javascript
{
  "error": {ERROR TYPE}
}
```

### Keywords

Facebook: facebook, fb

Instagram: instagram, ig

Github: github, gh

### Examples

```
https://ue.pascaltheelf.tk/facebook/zuck
```
