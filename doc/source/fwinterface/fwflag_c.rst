.. _fwflag_c:
==
-c
==
Switch
======

-c, --correl_field

Description
===========

unique id column, aka “group id” field

Argument and Default Value
==========================

Name of the table column

Details
=======

This field specifies which MySQL column will be used to identify “documents”, i.e. the “unit” of analysis of your command. If you’re looking to analyze the language of a Twitter user, :doc:`fwflag_c` will be something like user_id, whereas if you’re looking to analyze/extract features at a message level, :doc:`fwflag_c` should be something like message_id. This has to be a column in the message table (:doc:`fwflag_t`) and (if that’s what you’re doing) a column in the :doc:`fwflag_outcome_table`. 