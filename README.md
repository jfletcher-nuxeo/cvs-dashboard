# Nuxeo CVS Dashboard Parent Project

This repository is for building the Plugin and Marketplace package for the CVS Dashboard.

This sample uses [Nuxeo Data Visualzation](https://doc.nuxeo.com/x/WZCRAQ) to present a dashboard for the CVS demo.

# Building

Then navigate into the root folder for this project and run:

    mvn clean install

The Marketplace package will be placed in the `cvs-dashboard-mp/target` folder.

# Deploying

You may deploy the zip using `nuxeoctl` or the Nuxeo Admin Center.

# Usage

Once installed in the CVS demo, the dashboard is available at `http://yourserver/nuxeo/cvs-dashboard/`.

# Resources

## Reporting issues

Contact [jfletcher@nuxeo.com](mailto:jfletcher@nuxeo.com)

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris. More information is available at [www.nuxeo.com](http://www.nuxeo.com).