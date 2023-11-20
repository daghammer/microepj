# microepj
Very simple mock-up of EPJ integration with SFM - no backend SFM or HelseID integration

This file may be used together with SFM datashare api to establish a session with an SFM portal window.
Implemented as a stand-alone .html file with no server side logic.

See the SFM doc for details. Specifically: https://e-resept.atlassian.net/wiki/spaces/SFMDOK/pages/2160493151/Sequence+diagrams+and+examples+-+Integrating+EHR+with+the+SFM+client

microepj_paste.html has a copy-past function to receive information in response received in API call api/Session/create. This will populate the portal addresses (Velg portal), code and API endpoint. Just paste anywhere in the outer frame, except for input areas.

When you see the test "default backend - 404" - the selected portal is not available.


