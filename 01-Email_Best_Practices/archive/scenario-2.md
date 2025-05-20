# Scenario Description

**Address a bug report submitted by a colleague, where you suspect user
error rather than an actual code issue**

```
you're an entry-level dev working with a team testing a new feature for an
internal company tool. a colleague from QA has reported a bug, stating that
the tool isn't saving user settings correctly. after reviewing the report,
you suspect the issue might not be the code itself but rather possibly a
misunderstanding about how the settings are supposed to be used. reply
explaining your findings, suggesting they retry testing the feature with
specific instructions, and offer help if the issue persist
```

# Subject Line

Recent Bug Report - Possible Misunderstanding when Saving User Settings

# Body:

John Doe (Software QA Team),

&nbsp;&nbsp;&nbsp;&nbsp;Responding to the issue raised, that .json files appear in the 'data'
directory when they shouldn't and that no entry is created in the database,
it appears that the program was left running in 'dev mode'. I see the
expected behaviour here, save to the database and only create data files
when explicitly requested.

&nbsp;&nbsp;&nbsp;&nbsp;To resolve this, go to the 'program settings page', switch to the 'backend'
tab, and then uncheck the 'dev mode' option. Look under the 'data' heading now
and select the 'qa_database' to work with. When returning to the 'user settings'
a drop-down option under 'extract data' should now be available as well
wherein you may select the desired format (not just json).

&nbsp;&nbsp;&nbsp;&nbsp;Since development is still ongoing and our dev team needs to rapidly
iterate over the implementation of various features requested, we found it
prudent for us to create a 'dev mode' to suit our needs. Therefore, it will
remain in place until development is complete. Nonetheless, I see it fit to
now give visual indication whenever the software is left running in 'dev
mode'. This should avoid further confusion going forward. It shouldn't be
difficult, and so expect it implement by end-of-day tomorrow.

&nbsp;&nbsp;&nbsp;&nbsp;If you have any further ideas as to how to close the gap between expected
behaviour and intended usage I would really like to hear them! And if any
further issues arise don't hesitate to let me know; I will gladly work to
get them resolved.

Regards,\
Jose N. Olmos\
Entry-level Developer\
Internal Systems Dept.\
918.703.1949\
jose.olmos@atlasschool.com
