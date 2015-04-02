--------------   -------------------------------------------
**Title**        Apache Taverna: Sustaining research software at the Apache Software Foundation
**Authors**       [_Stian Soiland-Reyes_](http://orcid.org/0000-0001-9842-9718), [Ian Dunlop](http://orcid.org/0000-0001-7066-3350), [Alan R Williams](http://orcid.org/0000-0003-3156-2105), [Apache Taverna team](http://taverna.incubator.apache.org/about/)
**Affiliation**  Apache Software Foundation; [eScience Lab](http://www.cs.manchester.ac.uk/our-research/activities/e-science/), University of Manchester
**Contact**      [http://taverna.incubator.apache.org/contact](http://taverna.incubator.apache.org/contact)
**URL**          [http://taverna.incubator.apache.org/](http://taverna.incubator.apache.org/)
**License**      [Apache Software License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
--------------   -------------------------------------------

[Apache Taverna](http://taverna.incubator.apache.org/) is a
domain-independent *scientific workflow* system, encompassing a graphical
workbench, command line tools, server and APIs. Although Taverna
was conceived for
[bioinformatics](http://taverna.incubator.apache.org/introduction/taverna-in-use/bioinformatics),
its user base now also encompasses domains as
diverse as [astronomy](http://amiga.iaa.es/p/290-astrotaverna.htm),
[digital preservation](http://www.scape-project.eu/),
[biodiversity](http://www.biovel.eu/) and
[virtual physiology](http://www.vph-share.eu/).
Taverna has been an open source project since 2003, developed by the
[myGrid consortium](http://www.mygrid.org.uk/) and
originally led by the University of Manchester
and EMBL-EBI. In October 2014, Taverna became
an [incubating project](http://incubator.apache.org/) at the
[Apache Software Foundation](http://www.apache.org/) (ASF).

Here we describe our motivation for changing the *governance* and *ownership* of
the Taverna project, and reflect on our experience
and challenges in transitioning a University-led research software
activity to an open development process and
building a wider developer community.

*Research Software* supports scientists
and researchers; its development is usually funded for domain-specific projects
and made publicly available as Open Source through
code repositories ([GitHub](https://github.com/),
[BitBucket](https://bitbucket.org/)).
By the time research software develops into a mature code base
and gains a diverse user base, the initial funding and related projects may
already be finished, yet ownership and control of the project typically
remains with the original authors. Users and third-party developers have
the *source code*, but are often not included in project decisions,
and may not feel _ownership_ to contribute code, documentation or
support for others.

The original developers may eventually become involved in new projects that do not
directly relate to the original project, and may lose focus as the user base changes.
Thus it becomes critical to grow a sustainable and diverse
*developer community*, and to build an *open governance* model that encourages
engagement and commitment from everyone using the software. Efforts like the
[Software Sustainability Institute](http://software.ac.uk/) are
crucial, as it helps guide [research software engineers](http://www.rse.ac.uk/)
in best practices for making their research software open and maintainable.
Ultimately the success of an open source project should lead to a change of its
structure and management to include anyone in its further development.

For Taverna, we considered several options to reduce the lead role and
responsibility that the University of Manchester had, and
to move to a neutral ownership model where
any interested developers could contribute to Taverna's development
on an equal standing. One of the options was to create a Taverna Foundation,
but this would have required legal administration and a dedicated budget.

Another option was to assign copyright and management of the code to a
well-established software foundation
like the
[Software Freedom Conservancy](https://sfconservancy.org/),
the [GNU project](http://www.gnu.org/help/evaluation.html)
at the [Free Software Foundation](http://www.fsf.org/), the
[Eclipse Foundation](http://wiki.eclipse.org/Development_Resources/HOWTO/Starting_A_New_Project),
the [Outercurve Foundation](http://www.outercurve.org/) which is backed by Microsoft,
and the [Apache Software Foundation](http://apache.org/).
The different options come with implications for the
project's way of working, licensing, community, politics,
infrastructure and public impression - which must be evaluated
with regards to the particular research software project.

By choosing Apache as its new home, we put emphasis on the community
building, a strong and neutral governance model, and clear
intellectual property management, which we believe makes the project
more approachable for new participants and commercial entities.
While the initial months as an Apache Incubator involved a fair bit of
administrative overhead, such as moving mailing lists, transitioning web sites
and bug trackers and verifying dependency licensing and intellectual property
ownership of the donated source code, we feel this is offset already by an
increase in awareness in the community at large. Several new developers have
been attracted to the project, with many proposals and new ideas, including 4
[Google Summer of Code](https://www.google-melange.com/gsoc/homepage/google/gsoc2015)
student applications.
