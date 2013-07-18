opennms-nexus
=============

Repository for building a nexus maven proxy building OpenNMS.

How To Use
==========

1. Download the latest Nexus tar.gz from http://www.sonatype.org/nexus/archived/
2. Untar the archive, it will create 2 directories:
   * nexus-X.X.X
   * sonatype-work
3. Create the nexus conf directory: `mkdir -p sonatype-work/nexus/conf`
4. Copy the nexus/nexus.xml file from here to the sonatype-work/nexus/conf/ directory.
5. Start nexus.
6. Copy m2-home/settings.xml to ~/.m2/ if you don't have one already.  If you do
   already have one, copy the mirrors section to your existing config.
