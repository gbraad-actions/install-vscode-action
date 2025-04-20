Install VS Code on Windows
==========================


Installs VS Code on Windows runners

```yaml
    runs-on: windows-latest
    steps:
      - uses: gbraad-actions/install-vscode-action@main
      - name: Run VS Code serve-web
        run: |
          code serve-web --host 0.0.0.0 --without-connection-token
```
