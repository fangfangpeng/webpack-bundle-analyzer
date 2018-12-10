# Install
``` npm install --save-dev webpack-bundle-analyzer ```
# Usage (as a plugin)
``` 
const BundleAnalyzerPlugin = require('webpack-bundle-analyzer').BundleAnalyzerPlugin;
 
module.exports = {
  plugins: [
    new BundleAnalyzerPlugin()
  ]
}
* It will create an interactive treemap visualization of the contents of all your bundles.
