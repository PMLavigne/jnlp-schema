# JNLP Schemas
A collection of unofficial schema files for the Sun / Oracle .jnlp format

## Introduction
As far as I know, neither Sun nor the Oracle behemoth that devoured it ever released any schema files for the .jnlp format. This is a problem if, like me, you want to autogenerate classes based on schema files for serialization into the .jnlp format.

## Contents
So far, I have a basic automatically-generated schema for the base JNLP format, as well as (very limited) schemas for the jfx: and fx: namespaces that are added by JavaFX.

**I have basically taken this as far as my needs required and as such it is probably missing things.** Go ahead and submit a pull request if you want to add something I'm missing, I'd like to have it be as complete as possible but I don't really have the time to figure out the format entirely myself.

Also, I couldn't find any URL referenced for the "fx" namespace, so I made up a sensible one based on the "jfx" namespace. If you know of the "official" one please let me know so I can update it.

## Attribution
I started with this automatically-generated JNLP 1.6 schema, made by Roedy Green of [Canadian Mind Products](http://mindprod.com) who seems like a pretty rad dude:

http://mindprod.com/jgloss/jnlp.html

Mr. Green didn't put a license on that specific piece of code, but elsewhere he lists code with the following license:

>Licence: This software may be copied and used freely for any purpose but military. http://mindprod.com/contact/nonmil.html

I like that non-military-use clause, good for you Mr. Green :)

Other than the main jnlp.xsd file, the rest of the code so far has been written by myself, Patrick Lavigne.

## License
I've listed these derivative works as GPLv3, if anyone has an issue with that or if Mr. Green would like me to remove the code he generated please let me know. The non-military-use clause also applies here, and I have tried to reflect that in the file headers. Please see the LICENSE file for more information.

## Disclaimer
I don't own nor do I claim to own Java, the Java brand, the Java logo, a cup which can hold Java, Oracle, Sun, JNLP, or A good pair of pants that fit well and look good. All copyrights belong to their respective owners who are not me unless explicitly stated otherwise.

Don't sue me, I don't have any money anyway.