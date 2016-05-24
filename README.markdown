# Tumblr2Hatenablog

Tumblrからはてなブログに移行するためのPHPスクリプトです。

はてなブログにimport可能なwordpress形式のXMLを生成します。

http://help.hatenablog.com/entry/import-mt

This project is forked from [BenWard/tumblr2wordpress](https://github.com/BenWard/tumblr2wordpress) and this Tumblr2Wordpress is originally a project by Hao Chen <http://haochen.me/>, and you can find that branch of work at <http://code.google.com/p/tumblr2wordpress/>.

This work is licensed under the GPL v3 <http://www.gnu.org/licenses/gpl.html>

## Usage

You can use on http://tumblr2hatenablog.herokuapp.com/

### as a command line tool

- `% php index.php --username <your-tumblr-id> > export.xml`
  - options
    - `format`:
      - `html`: HTML
      - `text`: Plain Text
      - `none`: (default) Raw Input (preserving Markdown)

### as a webapp

- `% php -S 0.0.0.0:3000`
- access to http://localhost:3000
