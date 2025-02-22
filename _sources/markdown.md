# Definisi Sistem Persamaan Linear

Sistem persamaan linear merupakan salah satu topik yang penting dalam matematika. Sistem ini terdiri dari beberapa persamaan linear yang harus diselesaikan secara bersamaan. Persamaan linear sendiri merupakan persamaan yang memiliki bentuk umum seperti ax + by = c, di mana a, b, dan c adalah konstanta yang diketahui, sedangkan x dan y adalah variabel yang harus dicari.

Dalam sistem persamaan linear, terdapat dua jenis sistem yaitu sistem persamaan linear dengan dua variabel dan sistem persamaan linear dengan tiga variabel. Sistem persamaan linear dengan dua variabel memiliki dua persamaan dengan dua variabel yang harus dicari nilainya. Sedangkan sistem persamaan linear dengan tiga variabel memiliki tiga persamaan dengan tiga variabel yang harus dicari nilainya

## 

MyST stands for "Markedly Structured Text". It
is a slight variation on a flavor of markdown called "CommonMark" markdown,
with small syntax extensions to allow you to write **roles** and **directives**
in the Sphinx ecosystem.

For more about MyST, see [the MyST Markdown Overview](https://jupyterbook.org/content/myst.html).

## Sample Roles and Directives

Roles and directives are two of the most powerful tools in Jupyter Book. They
are like functions, but written in a markup language. They both
serve a similar purpose, but **roles are written in one line**, whereas
**directives span many lines**. They both accept different kinds of inputs,
and what they do with those inputs depends on the specific role or directive
that is being called.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
