# UWAGA!
W celu użycia skryptu należy się upewnić czy program ImageMagick ma włączone  uprawnienia do używania formatu PDF.
W tym celu należy dodać do pliku `/etc/ImageMagick-7/policy.xml` linijkę `<policy domain="coder" rights="read | write" pattern="PDF" />` tuż przed znacznikiem `</policymap>` (lub edytować istniejącą już linijkę dotyczącą formatu PDF).

