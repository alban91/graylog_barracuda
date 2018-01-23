# graylog_barracuda
Extractor.json contains all the extractors needed to construct fields out of barracuda firewall syslog messages.

In order to import:
1. Click 'System' menu and select 'Inputs'
2. On a syslog input section, click 'Manage extractors'
3. Click 'Actions' button (top right) and select 'Import extractors'
4. Copy and paste contents of extractor.json into the text field and click 'Add extractors to input' (below field)

Graylog team has said that importing extractors will be deprecated in favor of content packs which will include extractors along with dashboards and inputs to tie together.
