# Updating vocabulary

Vocabulary definitions are managed in vocab.csv. Add or change entries within this file. Regenerate shex.ttl, context.jsonld, and index.html as described below.

# Building index.html, shex.jsonld and shex.ttl

All files are based on vocab.csv,. Run `mk_vocab.rb` to build both `index.html`, `context.jsonld` and `shex.ttl`. Open index.html, and generate HTML to save over itself to remove ReSpec dependencies.
