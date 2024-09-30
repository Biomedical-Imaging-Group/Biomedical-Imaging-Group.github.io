.. Biomedical Imaging Group documentation master file, created by
   sphinx-quickstart on Mon Sep 30 17:18:47 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. Syntax
.. <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_

Syntax
======

*text italic*

**text bold**

`code`

``text blockquote``

<https://www.example.com>

---

[URL](https://www.example.com)

+++ some text



.. sidebar:: Optional Sidebar Title
   :subtitle: Optional Sidebar Subtitle

   Subsequent indented lines comprise
   the body of the sidebar, and are
   interpreted as body elements.

![fishy](images/logo_colab.png)

latex
-----
$$
e = mc^2
$$

$$
\begin{eqnarray}
y    & = & ax^2 + bx + c \\
f(x) & = & x^2 + 2xy + y^2
\end{eqnarray}
$$

Hence, for $\alpha \in (0, 1)$,
$$
\mathbb P (\alpha \bar{X} \ge \mu) \le \alpha;
$$

.. toctree:: 
   :maxdepth: 2

   Introduction

.. important::

   texte important

.. note::
   note

.. tip::
   tip

.. danger::
   danger

.. attention::
   attention

.. caution::
   caution

.. error::
   error

.. hint::
   hint

.. seealso::
   Python's :py:mod:`zipfile` module
      Documentation of Python's standard :py:mod:`zipfile` module.

   `GNU tar manual, Basic Tar Format <https://example.org>`_
      Documentation for tar archive files, including GNU tar extensions.

.. code:: python
   :number-lines:

   def my_function():
       "just a test"
       print(8/2)

.. class:: highlights
..

    Block quote text.

Math
----------
.. math::

  α_t(i) = P(O_1, O_2, … O_t, q_t = S_i λ)

.. raw:: latex

   \alpha^2 + \beta_2

Epigraph
----------
.. epigraph::

   No matter where you go, there you are.

   -- Buckaroo Banzai

.. compound::

   The 'rm' command is very dangerous.  If you are logged
   in as root and enter ::

       cd /
       rm -rf *

   you will erase the entire contents of your file system.


Container
----------
.. container:: custom

   CONTAINER This paragraph might be rendered in a custom way.

Table
----------

.. table:: Truth table for "not"
   :widths: auto

   =====  =====
     A    not A
   =====  =====
   False  True
   True   False
   =====  =====

List table
----------
.. list-table:: Frozen Delights!
   :widths: 15 10 30
   :header-rows: 1

   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!

.. code-block::
   :caption: Title of code block

       The output of this line starts with four spaces.

.. code-block::

       The output of this line has no spaces at the beginning.


HTML
----------
.. raw:: html

   <hr width=50 size=10 background=red>

Footnote
----------
Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.

Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] Book or article reference, URL or whatever.

Special
----------
.. class:: special

This is a "special" paragraph.

.. class:: exceptional remarkable

An Exceptional Section
======================

This is an ordinary paragraph.

.. class:: multiple

   First paragraph.

   Second paragraph.

