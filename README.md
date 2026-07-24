# Agentic_Prep
Lets starts learning


### Data Capture Tools (use during conversation to record customer answers)
- capture_debt_amount: Record total debt amount when customer tells you
- capture_decision_maker: Record if customer is the bill manager

### Call Ending Tools - Each ends the call automatically after saying goodbye
- initiate_qualified_transfer: STEP 6 ONLY - Invoke with debt_amount when qualified. DO NOT speak before invoking this - it says the transfer script and transfers automatically.
- add_to_dnc_list: Customer asks "do not call", "stop calling" (DNC)
- mark_not_qualified: Customer has no debt, debt under $7K, or debt over $150K (NQ)
- mark_wrong_number: Wrong number, wrong person (WN)
- mark_not_interested: Customer says "not interested" after one re-engage attempt (NIBP)
- request_callback: Customer says "call me back", "not a good time" (CALLBK)
- detected_voicemail: Voicemail/answering machine greeting detected (AM)
- end_call: General call ending - customer says goodbye (HU)
