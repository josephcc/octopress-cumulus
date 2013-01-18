
WP-Cumulus for Octopress, originally developed by weefselkweekje and LukeMorton for WordPress.
Ported to Octopress by Joseph Chang.

Link to WP-Cumulus: http://wordpress.org/extend/plugins/wp-cumulus/

Description:
------------
3D rotating tagcloud for Octopress, ported from WP-cumulus.

Demo:
--------
http://joseph.nlpweb.org/blog    
http://blog.ashwani.co.in

Syntax:
-------
    {% category_cloud %} for default colors

    OR

    {% tag_cloud bgcolor:#ffffff tcolor1:#00aa00 tcolor2:#00dd00 hicolor:#ff3333 %}

Example:
--------
In template files, add the following markups.

### source/_includes/custom/asides/category_cloud.html ###

    <section>
      <h1>Tag Cloud</h1>
        <span id="tag-cloud">{% tag_cloud bgcolor:#ffffff tcolor1:#00aa00 tcolor2:#00dd00 hicolor:#ff3333%}</span>
    </section>


License:
---------
WP-Cumulus is under GPLv3. However, original javascript and php code are not used, only tagcloud.swf
is adopted. This ruby code is under MIT License.

GPLv3: http://gplv3.fsf.org
MIT License: http://opensource.org/licenses/MIT

