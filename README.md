# Instructions

#### 1. Go to C:\Program Files\VSCodium\resources\app
#### 2. Open product.json in text editor
#### 3. replace the extensionsGallery section with below snippet.

```
"extensionsGallery": {
    "serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
    "cacheUrl": "https://vscode.blob.core.windows.net/gallery/index",
    "itemUrl": "https://marketplace.visualstudio.com/items"
  },  
```

#### 4. Save the file and relaunch the VSCodium.
#### 5. You should be able to see marketplace extensions such as "Salesforce Extension Pack"
#### 6. Done.

## If still doesnt work then :
#### 1. Press F1 or command pallet(ctrl+shift+p)
#### 2. Preferences: Open User Settings
#### 3. search "proxy"
#### 4. edit using "Edit in settings.json" link.
#### 5. remove lines containing "proxy" properties
#### 6. save.
#### 7. relaunch VSCodium.

## If still doesnt work then :
#### 1. Press F1 or command pallet(ctrl+shift+p)
#### 2. Preferences: Open User Settings
#### 3. search "proxy" 
#### 4. set "Http: Proxy Support" dropdown value to "fallback"
#### 5. save.
#### 6. relaunch the VSCodium
