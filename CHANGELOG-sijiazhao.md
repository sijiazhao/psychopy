# 2025.1.1

**experiment/_experiment.py**
- Move writeWindowCodeJS before code blocks

**experiment/flow.py**
- Set title, logoURL, text from helper.options
- Use completionMessage and exitQuitMessage
- Add BeforeExperiment.run() to run queued tasks
- Wrap psychoJS.start inside function startPsychoJS()

**experiment/components/settings/__init__.py**
- Add participant ID and __option fields
- Use custom PsychoJS, add helper.js
- Turn off debug by default, add extra newline at end
- Set options from expInfo, add Overrides, add BeforeExperiment

**experiment/components/settings/Js_htmlHeader.tmpl**
- Simple title
- Add custom stylesheet
- Remove support for legacy browsers

**experiment/components/settings/JS_setupExp.tmpl**
- Add sijiazhao to version info

**experiment/routines/_base.py**
- Remove return from quitPsychoJS, use escapeQuitMessage