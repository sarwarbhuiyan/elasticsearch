SONATYPE_NEXUS_REPOSITORY = "http://oss.sonatype.org/content/repositories/snapshots"
LUCENE_SNAPSHOT_VERSION = "1682335"
LUCENE_VERSION = "5.2.0-snapshot-" + LUCENE_SNAPSHOT_VERSION

ELASTICSEARCH_LUCENE_REPOSITORY = "https://download.elasticsearch.org/lucenesnapshots/" + LUCENE_SNAPSHOT_VERSION
JACKSON_VERSION = "2.5.3"

maven_jar(
    name = "lucene-core",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-core",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-core-jar",
    actual = "@lucene-core//jar"
)

maven_jar(
    name = "lucene-backward-codecs",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-backward-codecs",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-backward-codecs-jar",
    actual = "@lucene-backward-codecs//jar"
)

maven_jar(
    name = "lucene-analyzers-common",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-analyzers-common",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-analyzers-common-jar",
    actual = "@lucene-analyzers-common//jar"
)

maven_jar(
    name = "lucene-queries",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-queries",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-queries-jar",
    actual = "@lucene-queries//jar"
)

maven_jar(
    name = "lucene-memory",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-memory",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-memory-jar",
    actual = "@lucene-memory//jar"
)

maven_jar(
    name = "lucene-highlighter",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-highlighter",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-highlighter-jar",
    actual = "@lucene-highlighter//jar"
)

maven_jar(
    name = "lucene-queryparser",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-queryparser",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-queryparser-jar",
    actual = "@lucene-queryparser//jar"
)

maven_jar(
    name = "lucene-suggest",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-suggest",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-suggest-jar",
    actual = "@lucene-suggest//jar"
)

maven_jar(
    name = "lucene-misc",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-misc",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-misc-jar",
    actual = "@lucene-misc//jar"
)

maven_jar(
    name = "lucene-join",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-join",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-join-jar",
    actual = "@lucene-join//jar"
)

maven_jar(
    name = "lucene-spatial",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-spatial",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-spatial-jar",
    actual = "@lucene-spatial//jar"
)

maven_jar(
    name = "lucene-expressions",
    group_id = "org.apache.lucene",
    artifact_id = "lucene-expressions",
    version = LUCENE_VERSION,
    repositories = [ELASTICSEARCH_LUCENE_REPOSITORY]
)

bind(
    name = "lucene-expressions-jar",
    actual = "@lucene-expressions//jar"
)

maven_jar(
    name = "spatial4j",
    group_id = "com.spatial4j",
    artifact_id = "spatial4j",
    version = "0.4.1",

)

bind(
    name = "spatial4j-jar",
    actual = "@spatial4j//jar"
)

maven_jar(
    name = "guava",
    group_id = "com.google.guava",
    artifact_id = "guava",
    version = "18.0",

)

bind(
    name = "guava-jar",
    actual = "@guava//jar"
)

maven_jar(
    name = "hppc",
    group_id = "com.carrotsearch",
    artifact_id = "hppc",
    version = "0.7.1",

)

bind(
    name = "hppc-jar",
    actual = "@hppc//jar"
)

maven_jar(
    name = "joda-time",
    group_id = "joda-time",
    artifact_id = "joda-time",
    version = "2.7",

)

bind(
    name = "joda-time-jar",
    actual = "@joda-time//jar"
)

maven_jar(
    name = "netty",
    group_id = "io.netty",
    artifact_id = "netty",
    version = "3.10.0.Final",

)

bind(
    name = "netty-jar",
    actual = "@netty//jar"
)

maven_jar(
    name = "jackson-core",
    group_id = "com.fasterxml.jackson.core",
    artifact_id = "jackson-core",
    version = JACKSON_VERSION,

)

bind(
    name = "jackson-core-jar",
    actual = "@jackson-core//jar"
)

maven_jar(
    name = "jackson-dataformat-smile",
    group_id = "com.fasterxml.jackson.dataformat",
    artifact_id = "jackson-dataformat-smile",
    version = JACKSON_VERSION,

)

bind(
    name = "jackson-dataformat-smile-jar",
    actual = "@jackson-dataformat-smile//jar"
)

maven_jar(
    name = "jackson-dataformat-yaml",
    group_id = "com.fasterxml.jackson.dataformat",
    artifact_id = "jackson-dataformat-yaml",
    version = JACKSON_VERSION,

)

bind(
    name = "jackson-dataformat-yaml-jar",
    actual = "@jackson-dataformat-yaml//jar"
)

maven_jar(
    name = "jackson-dataformat-cbor",
    group_id = "com.fasterxml.jackson.dataformat",
    artifact_id = "jackson-dataformat-cbor",
    version = JACKSON_VERSION,

)

bind(
    name = "jackson-dataformat-cbor-jar",
    actual = "@jackson-dataformat-cbor//jar"
)

maven_jar(
    name = "jts",
    group_id = "com.vividsolutions",
    artifact_id = "jts",
    version = "1.13",

)

bind(
    name = "jts-jar",
    actual = "@jts//jar"
)

maven_jar(
    name = "commons-lang3",
    group_id = "org.apache.commons",
    artifact_id = "commons-lang3",
    version = "3.3.2",

)

bind(
    name = "commons-lang3-jar",
    actual = "@commons-lang3//jar"
)

maven_jar(
    name = "sigar",
    group_id = "org.fusesource",
    artifact_id = "sigar",
    version = "1.6.4",

)

bind(
    name = "sigar-jar",
    actual = "@sigar//jar"
)

maven_jar(
    name = "jna",
    group_id = "net.java.dev.jna",
    artifact_id = "jna",
    version = "4.1.0",

)

bind(
    name = "jna-jar",
    actual = "@jna//jar"
)

maven_jar(
    name = "commons-cli",
    group_id = "commons-cli",
    artifact_id = "commons-cli",
    version = "1.2",

)

bind(
    name = "commons-cli-jar",
    actual = "@commons-cli//jar"
)

maven_jar(
    name = "compress-lzf",
    group_id = "com.ning",
    artifact_id = "compress-lzf",
    version = "1.0.2",

)

bind(
    name = "compress-lzf-jar",
    actual = "@compress-lzf//jar"
)

maven_jar(
    name = "log4j",
    group_id = "log4j",
    artifact_id = "log4j",
    version = "1.2.17",

)

bind(
    name = "log4j-jar",
    actual = "@log4j//jar"
)

maven_jar(
    name = "apache-log4j-extras",
    group_id = "log4j",
    artifact_id = "apache-log4j-extras",
    version = "1.2.17",

)

bind(
    name = "log4j-extras-jar",
    actual = "@apache-log4j-extras//jar"
)

maven_jar(
    name = "slf4j-api",
    group_id = "org.slf4j",
    artifact_id = "slf4j-api",
    version = "1.6.2",

)

bind(
    name = "slf4j-api-jar",
    actual = "@slf4j-api//jar"
)

maven_jar(
    name = "slf4j-log4j12",
    group_id = "org.slf4j",
    artifact_id = "slf4j-log4j12",
    version = "1.6.2",

)

bind(
    name = "slf4j-log4j12-jar",
    actual = "@slf4j-log4j12//jar"
)

maven_jar(
    name = "groovy-all",
    group_id = "org.codehaus.groovy",
    artifact_id = "groovy-all",
    version = "2.4.0",
)

bind(
    name = "groovy-all-jar",
    actual = "@groovy-all//jar"
)

maven_jar(
    name = "mustache-compiler",
    group_id = "com.github.spullara.mustache.java",
    artifact_id = "compiler",
    version = "0.8.13",
)

bind(
    name = "mustache-compiler-jar",
    actual = "@mustache-compiler//jar"
)

maven_jar(
    name = "t-digest",
    group_id = "com.tdunning",
    artifact_id = "t-digest",
    version = "3.0",
)

bind(
    name = "t-digest-jar",
    actual = "@t-digest//jar"
)
