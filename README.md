RH-SSO BOMs
==========

The RH-SSO BOM's project provides Maven BOM files which manages the version of the dependencies you use in your project, ensuring you always get a compatible stack.

Usage
-----

To use the BOM, import it into your dependency management. For adapters import the following BOM:

    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>com.redhat.bom.rh-sso</groupId>
                <artifactId>rh-sso-adapter-bom</artifactId>
                <version>7.3.0.GA</version>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

For server extensions import the following BOM:

    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>com.redhat.bom.rh-sso</groupId>
                <artifactId>rh-sso-spi-bom</artifactId>
                <version>7.3.0.GA</version>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

