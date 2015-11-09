# Nuxeo DAM Dashboard Sample MP

This repository is for building the Marketplace package for the Nuxeo DAM Dashboard plug-in.

This sample uses [Nuxeo Data Visualzation](https://doc.nuxeo.com/x/WZCRAQ) to create a dashboard for the Nuxeo DAM add-on.

# Building

You need to first build the [nuxeo-dam-dashboard-plugin](https://github.com/jfletcher-nuxeo/nuxeo-dam-dashboard-plugin) project.

Then navigate into the root folder for this project and run:

    mvn clean install

The Marketplace package will be placed in the `marketplace/target` folder.

## Deploying

You may deploy the zip using `nuxeoctl` or the Nuxeo Admin Center.

## Usage

Navigate to `http://yourserver/nuxeo/dam-dashboard`.

# Resources

## Reporting issues

Contact [jfletcher@nuxeo.com](mailto:jfletcher@nuxeo.com)

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).