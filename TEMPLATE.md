# :wave: Hello, I'm {{ NAME }}

I joined GitHub on `{{ f.date(REGISTRATION_DATE, {dateStyle:"short"}) }}`. I contributed to `{{ REPOSITORIES_CONTRIBUTED_TO }}` repositories and made `{{ COMMITS }}` commits.
___

<%- await embed(`example-languages-pdf`, {languages:true, languages_details:"percentage, bytes-size", config_display:"large"}) %>
