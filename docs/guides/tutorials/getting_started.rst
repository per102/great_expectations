.. _tutorials__getting_started:

###############
Getting started
###############

Welcome to Great Expectations! This tutorial will help you set up your first deployment of Great Expectactions. We'll also introduce important concepts, with links to detailed material you can dig into later.

Please follow these steps to get started:

.. raw:: html

   <embed>
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">
      <style>
         .custom-indented-paragraph {
            margin-left: 70px;
         }
      </style>
   </embed>

.. raw:: html

   <embed>
      <h2><span class="fa-stack">
         <span class="fa fa-circle-o fa-stack-2x"></span>
         <strong class="fa-stack-1x">
            1
         </strong>
      </span> Initialize a DataContext</h2>
   </embed>

.. container:: custom-indented-paragraph

   In Great Expectations, your :ref:`Data Context <reference__core_concepts__data_contexts>` manages boilerplate configuration. Using a DataContext is almost always the fastest way to get up and running, even though some teams don't need every component of a DataContext.
   
   Follow these instructions to :ref:`tutorials__getting_started__initialize_a_data_context`.

..
   Alternatively, if you really want to learn the components of Great Expectations without a DataContext, check out `A magic-free introduction to Great Expectations.`_

.. raw:: html

   <embed>
      <h2><span class="fa-stack">
         <span class="fa fa-circle-o fa-stack-2x"></span>
         <strong class="fa-stack-1x">
            2
         </strong>
      </span> Connect to data</h2>
   </embed>

.. container:: custom-indented-paragraph

   Once you have a Data Context, you'll want to connect to data. In Great Expectations, :ref:`Datasources <reference__core_concepts__datasources>` simplify connections, by managing configuration and providing a consistent, cross-platform API for referencing data.
   
   Check out :ref:`tutorials__getting_started__connect_to_data` to learn how to configure your first Datasource.

.. raw:: html

   <embed>
      <h2><span class="fa-stack">
         <span class="fa fa-circle-o fa-stack-2x"></span>
         <strong class="fa-stack-1x">
            3
         </strong>
      </span> Create your first Expectations</h2>
   </embed>

.. container:: custom-indented-paragraph

   :ref:`Expectations <reference__core_concepts__expectations>` are the workhorse abstraction in Great Expectations, a flexible, declarative language for describing the expected characteristics of data.

   Click through to :ref:`tutorials__getting_started__create_your_first_expectations`.

.. raw:: html

   <embed>
      <h2><span class="fa-stack">
         <span class="fa fa-circle-o fa-stack-2x"></span>
         <strong class="fa-stack-1x">
            4
         </strong>
      </span> Set up Data Docs</h2>
   </embed>

.. container:: custom-indented-paragraph

   One of Great Expectations' core promises is that your tests and documentation will always stay in sync, because docs and tests are both :ref:`compiled from the same Expectations <reference__core_concepts__data_docs>`.
   
   To see how this works, follow :ref:`these instructions <tutorials__getting_started__set_up_data_docs>` to set up a local static website for your data documentation. Later, you'll be able to host the site remotely, or integrate content generated by Great Expectations into an metadata store.

.. raw:: html

   <embed>
      <h2><span class="fa-stack">
         <span class="fa fa-circle-o fa-stack-2x"></span>
         <strong class="fa-stack-1x">
            5
         </strong>
      </span> Set up your first Checkpoint</h2>
   </embed>

.. container:: custom-indented-paragraph

   In normal usage, the best way to validate data is with a :ref:`Checkpoint`. Checkpoints simplify deployment, by pre-specifying the data and Expectations that to validate at any given point in your data infrastructure, along with follow-up actions to trigger based on the results of validation.

   Follow these instructions to :ref:`set up your first Checkpoint`.

.. raw:: html

   <embed>
      <h2><span class="fa-stack">
         <span class="fa fa-circle-o fa-stack-2x"></span>
         <strong class="fa-stack-1x">
            6
         </strong>
      </span> Customize your deployment</h2>
   </embed>

.. container:: custom-indented-paragraph

   By this point, you'll have your first, working deployment of Great Expectations. The next step is to :ref:`tutorials__getting_started__customize_your_deployment`.
   
   Data Contexts make this modular, so that you can add or swap out one component at a time. Most of these changes are quick, incremental steps---so you can upgrade from a basic demo deployment to a full production deployment at your own pace, and be confident that your Data Context will continue to work at every step along the way.
   
-----

Table of contents for Getting Started:

.. toctree::
   :maxdepth: 1

   /tutorials/getting_started/initialize_a_data_context
   /tutorials/getting_started/connect_to_data
   /tutorials/getting_started/create_your_first_expectations
   /tutorials/getting_started/set_up_data_docs
   /tutorials/getting_started/set_up_your_first_checkpoint
   /tutorials/getting_started/customize_your_deployment
