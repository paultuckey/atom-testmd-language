# Language-testmd package for Atom

Adds syntax highlighting and snippets to testmd (Test Markdown) files in Atom.

## Snippets

### From TESTMD file

| Snippets      | Result                                         |
| ------------- |:----------------------------------------------:|
| `<`           | &lt;!NAME element&gt;                          |
| `element`     | &lt;!ELEMENT name (content)&gt;                |
| `attlist`     | &lt;!ATTLIST element attribute TYPE #VALUE&gt; |
| `entity`      | &lt;!ENTITY name "value"&gt;                   |

### From MD file

| Snippets          | Result                                         |
| ----------------- |:----------------------------------------------:|
| `dtd-simple`      | &lt;!NAME element&gt;                          |
| `dtd-element`     | &lt;!ELEMENT name (content)&gt;                |
| `dtd-attlist`     | &lt;!ATTLIST element attribute TYPE #VALUE&gt; |
| `dtd-entity`      | &lt;!ENTITY name "value"&gt;                   |
| `dtd-local`       | Generates a local DTD environment              |
| `dtd-import`      | Import an external DTD file                    |

## Bugs

Feel free to report an issue and make a request.


# Deploy to atom locally

rm -rf ~/.atom/packages/language-testmd/ && \
mkdir -p ~/.atom/packages/language-testmd/ && \
cp -R ~/co/atom-testmd-language/ ~/.atom/packages/language-testmd/

