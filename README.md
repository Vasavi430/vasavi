{
  "advancedSettings": {
    "loggingSettings": {
      "disableLogging": true
    }
  },
  "currentFlow": {
    "displayName": "Trace a Shipment",
    "name": "projects/wise-colledge-gecq/locations/global/agents/810654b5-79a9-43ad-a735-22bdeefe116d/flows/dbef2ed0-b28a-41e3-bfe1-dcf2119fe037"
  },
  "currentPage": {
    "displayName": "Service within India",
    "name": "projects/wise-colledge-gecq/locations/global/agents/810654b5-79a9-43ad-a735-22bdeefe116d/flows/dbef2ed0-b28a-41e3-bfe1-dcf2119fe037/pages/ab1931d9-7485-4800-9fd0-6cb4daed1a9c"
  },
  "diagnosticInfo": {
    "Alternative Matched Intents": [
      {
        "Active": true,
        "Score": 0.5339536070823669,
        "Type": "NLU",
        "Id": "33893ffc-42ad-4e5e-879a-eced5231481e",
        "DisplayName": "Serviceable Location"
      }
    ],
    "Response Id": "6e41c34b-5aed-4fa3-b7f5-9adeb55bc801",
    "Triggered Transition Names": [
      "c62c0687-f41e-4d60-a3f3-d92533b6f577"
    ],
    "Transition Targets Chain": [
      {
        "TargetPage": "ab1931d9-7485-4800-9fd0-6cb4daed1a9c"
      }
    ],
    "Execution Sequence": [
      {
        "Step 1": {
          "Type": "INITIAL_STATE",
          "InitialState": {
            "MatchedIntent": {
              "Type": "NLU",
              "Active": true,
              "DisplayName": "Serviceable Location",
              "Id": "33893ffc-42ad-4e5e-879a-eced5231481e",
              "Score": 0.5339536070823669
            },
            "FlowState": {
              "Version": 0,
              "PageState": {
                "ActiveParameter": "PIN_SEN",
                "Status": "PROCESSING_FORM",
                "Name": "Service within India",
                "PageId": "ab1931d9-7485-4800-9fd0-6cb4daed1a9c",
                "FormFilled": false
              },
              "Name": "Trace a Shipment",
              "FlowId": "dbef2ed0-b28a-41e3-bfe1-dcf2119fe037"
            }
          }
        }
      },
      {
        "Step 2": {
          "FunctionExecution": {
            "Responses": [
              {
                "source": "VIRTUAL_AGENT",
                "text": {
                  "text": [
                    "Please Select"
                  ]
                },
                "responseType": "HANDLER_PROMPT"
              },
              {
                "payload": {
                  "richContent": [
                    {
                      "options": [
                        {
                          "text": "Service within India"
                        },
                        {
                          "text": "Service other countries"
                        }
                      ],
                      "type": "chips"
                    }
                  ]
                },
                "responseType": "HANDLER_PROMPT",
                "source": "VIRTUAL_AGENT"
              }
            ]
          },
          "Type": "STATE_MACHINE",
          "StateMachine": {
            "FlowState": {
              "PageState": {
                "ActiveParameter": "PIN_SEN",
                "Name": "Service within India",
                "FormFilled": false,
                "PageId": "ab1931d9-7485-4800-9fd0-6cb4daed1a9c",
                "Status": "TRANSITION_ROUTING"
              },
              "Version": 0,
              "FlowId": "dbef2ed0-b28a-41e3-bfe1-dcf2119fe037",
              "Name": "Trace a Shipment"
            },
            "FlowLevelTransition": true,
            "TriggeredTransitionRouteId": "c62c0687-f41e-4d60-a3f3-d92533b6f577",
            "TargetPage": "ab1931d9-7485-4800-9fd0-6cb4daed1a9c",
            "TriggeredIntent": "Serviceable Location"
          }
        }
      },
      {
        "Step 3": {
          "Type": "STATE_MACHINE",
          "FunctionExecution": {},
          "StateMachine": {
            "FlowState": {
              "PageState": {
                "Name": "Service within India",
                "PageId": "ab1931d9-7485-4800-9fd0-6cb4daed1a9c",
                "FormFilled": false,
                "ActiveParameter": "PIN_SEN",
                "Status": "PROCESSING_FORM"
              },
              "Name": "Trace a Shipment",
              "FlowId": "dbef2ed0-b28a-41e3-bfe1-dcf2119fe037",
              "Version": 0
            }
          }
        }
      }
    ],
    "Session Id": "f503a2-43b-436-5d5-c02ffcb07"
  },
  "formFillingInfo": {
    "entityType": "projects/-/locations/-/agents/-/entityTypes/sys.number",
    "parameter": "PIN_SEN"
  },
  "generativeInfo": {
    "actionTracingInfo": {
      "actions": [
        {
          "userUtterance": {
            "text": "Service within India"
          }
        },
        {
          "agentUtterance": {
            "text": "Please Select"
          }
        }
      ],
      "conversationState": "OUTPUT_STATE_PENDING",
      "name": "projects/wise-colledge-gecq/locations/global/agents/810654b5-79a9-43ad-a735-22bdeefe116d/playbooks/-/examples/-"
    }
  },
  "intent": {
    "displayName": "Serviceable Location",
    "name": "projects/wise-colledge-gecq/locations/global/agents/810654b5-79a9-43ad-a735-22bdeefe116d/intents/33893ffc-42ad-4e5e-879a-eced5231481e"
  },
  "intentDetectionConfidence": 0.5339536,
  "languageCode": "en",
  "match": {
    "confidence": 0.5339536,
    "intent": {
      "displayName": "Serviceable Location",
      "name": "projects/wise-colledge-gecq/locations/global/agents/810654b5-79a9-43ad-a735-22bdeefe116d/intents/33893ffc-42ad-4e5e-879a-eced5231481e"
    },
    "matchType": "INTENT",
    "resolvedInput": "Service within India"
  },
  "responseMessages": [
    {
      "responseType": "HANDLER_PROMPT",
      "source": "VIRTUAL_AGENT",
      "text": {
        "redactedText": [
          "Please Select"
        ],
        "text": [
          "Please Select"
        ]
      }
    },
    {
      "payload": {
        "richContent": [
          {
            "options": [
              {
                "text": "Service within India"
              },
              {
                "text": "Service other countries"
              }
            ],
            "type": "chips"
          }
        ]
      },
      "responseType": "HANDLER_PROMPT",
      "source": "VIRTUAL_AGENT"
    }
  ],
  "text": "Service within India"
}
