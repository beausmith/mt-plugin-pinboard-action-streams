# Pinboard Action Streams, a plugin for Movable Type

Authors: Beau Smith  
Copyright: 2010 Beau Smith  
License: [Artistic License 2.0](http://www.opensource.org/licenses/artistic-license-2.0.php)  
Site: $PluginSite (html page with more info on author's site, plugins.mt.org, or GitHub)  

## Overview

Aggregates user activity from a Pinboard.in account into Action Streams (which is bundled with Movable Type)


## Features

* feature
    * sub feature


## Requirements

* MT 4.x


## Installation

1. Move the PinboardActionStreams plugin directory to the MT `plugins` directory.
2. Move the PinboardActionStreams mt-static directory to the `mt-static/plugins` directory.

    Should look like this when installed:

        $MT_HOME/
            plugins/
                PinboardActionStreams/
                    (plugin files here)
            mt-static/
                plugins/
                    PinboardActionStreams/
                        (plugin static files here)

    [More in-depth plugin installation instructions](http://tinyurl.com/easy-plugin-install).

3. Add the following CSS to the Action Streams CSS file (`$MT_HOME/mt-static/plugins/ActionStreams/css/action-streams.css`):

        .service-Pinboard { background-image: url(/mt-static/plugins/PinboardActionStreams/images/redpin.gif); }

    or add this to the blogs css file index template:

        .service-Pinboard { background-image: url(<$mt:BlogURL$>mt-static/plugins/PinboardActionStreams/images/redpin.gif); }


## Desired Feature Wish List

* **add tag feeds** - code is commented out as Pinboard.in doesn't yet support global tag feeds


## Support

This plugin is not an official Beau Smith release, and as such support from Beau Smith for this plugin is not available.