# Selenium Tutorial
## Using either the Selenium IDE (https://www.seleniumhq.org/selenium-ide/) (Links to an external site.)Links to an external site. or the manual tutorial (https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Your_own_automation_environment) (Links to an external site.)Links to an external site. write a test that go and visits your favorite site, types in a search term, and clicks on the search term results. Save the file from the IDE or from the manual tutorial and upload it to your github account.

{
  "id": "2d5552d7-2536-4ac7-96ac-ba37fa428cbc",
  "version": "2.0",
  "name": "Seleniumtutorial",
  "url": "https://www.crunchyroll.com/",
  "tests": [{
    "id": "d91ab23a-6b60-4c2d-9272-ab62aa5d4959",
    "name": "Crunchyrollsearch",
    "commands": [{
      "id": "87af2abd-9947-4d5b-ad99-e67738bfdd4e",
      "comment": "",
      "command": "open",
      "target": "https://www.crunchyroll.com/",
      "targets": [],
      "value": ""
    }, {
      "id": "f7318800-4f87-4b12-8ee5-7ab00a09a210",
      "comment": "",
      "command": "setWindowSize",
      "target": "974x1040",
      "targets": [],
      "value": ""
    }, {
      "id": "96332bef-02a4-43f8-ac88-0924d40000bb",
      "comment": "",
      "command": "click",
      "target": "css=#header_menubar_beta > ul",
      "targets": [
        ["css=#header_menubar_beta > ul", "css:finder"],
        ["xpath=//nav[@id='header_menubar_beta']/ul", "xpath:idRelative"],
        ["xpath=//ul", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "fdcb1dea-8cda-4978-a4db-680e899ded01",
      "comment": "",
      "command": "click",
      "target": "css=#header_show_search_button svg",
      "targets": [
        ["css=#header_show_search_button svg", "css:finder"]
      ],
      "value": ""
    }, {
      "id": "fe358319-2cc5-4fe9-9eef-596b6c221c7a",
      "comment": "",
      "command": "click",
      "target": "id=header_search_input",
      "targets": [
        ["id=header_search_input", "id"],
        ["name=q", "name"],
        ["css=#header_search_input", "css:finder"],
        ["xpath=//input[@id='header_search_input']", "xpath:attributes"],
        ["xpath=//form[@id='header_search_form']/div/input[2]", "xpath:idRelative"],
        ["xpath=//input[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "d592efbe-8d88-4fa1-8d8b-9b209e010afe",
      "comment": "",
      "command": "type",
      "target": "id=header_search_input",
      "targets": [
        ["id=header_search_input", "id"],
        ["name=q", "name"],
        ["css=#header_search_input", "css:finder"],
        ["xpath=//input[@id='header_search_input']", "xpath:attributes"],
        ["xpath=//form[@id='header_search_form']/div/input[2]", "xpath:idRelative"],
        ["xpath=//input[2]", "xpath:position"]
      ],
      "value": "The Rising of the Shield Hero"
    }, {
      "id": "29fdbb0e-25c4-4ad9-9099-dde0226e4f25",
      "comment": "",
      "command": "click",
      "target": "id=header_search_form",
      "targets": [
        ["id=header_search_form", "id"],
        ["css=#header_search_form", "css:finder"],
        ["xpath=//form[@id='header_search_form']", "xpath:attributes"],
        ["xpath=//div[@id='header_container']/form", "xpath:idRelative"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "17d8705d-e234-4d00-84e0-1856fc186649",
      "comment": "",
      "command": "click",
      "target": "css=.button-label",
      "targets": [
        ["css=.button-label", "css:finder"],
        ["xpath=//button[@id='header_search_submit_beta']/span", "xpath:idRelative"],
        ["xpath=//button/span", "xpath:position"],
        ["xpath=//span[contains(.,'Search')]", "xpath:innerText"]
      ],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "c9ad6803-2cf7-4452-b1ba-4e3a31cdff54",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["d91ab23a-6b60-4c2d-9272-ab62aa5d4959"]
  }],
  "urls": ["https://www.crunchyroll.com/"],
  "plugins": []
}
