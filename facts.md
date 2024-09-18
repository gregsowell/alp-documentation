# Facts Section

Ascender Ledger Pro was initially created to collect fact information. Fact information is gathered by Ansible, which it does by default, on each host. It collects information such as IP address, partition information, drive utilization, operating system, etc.

## Fact Filtering

Filtering options are hosts, facts, type, and search.

Once a filter option is chosen, a secondary box appears. This box allows for the filter criteria to be specified. If it is a filter type that has a list associated with it, like hosts or facts, you have the ability to simply start typing the name of the object you wish to specify, and it will be narrowed down.

When choosing filter types, only a single filter type may be used at a time. For example, you can only specify a single fact type or a single host. However, you can have compound filter options, like choosing both a host and a fact type simultaneously if desired.

Each filter item that is added shows up to the right of the filters list. If you navigate away from the facts section and return, the filter will remain in place. Clicking the trash can icon will remove the filters.

Once a filter is added, the **Create** button can be clicked to save the item. A dialog box will pop up prompting for a name to be given to the created filter. Once this is completed, it will appear in the **Select Saved Filters** combo box. To utilize one of the saved filters, simply click the **Saved Filter** combo box and choose your option.

## Fact Search

To the right is the search box. The search box allows you to narrow down the information that is currently presented in the list. If no filtering is in place, it will start matching values from everything presented in the current list. If filtering is applied, then only information from the filtered list will be found via the search box.

## Export

Exporting options exist to the right above the search box. These options include **Copy**, **CSV**, **PDF**, and **Print**. 

- **Copy** will copy the text with tabs between the information.
- **CSV** will download a CSV file.
- **PDF** will create a PDF version of the information.
- **Print** will open the print dialog box.

If filtering and/or search are utilized, then the export options will only export the information shown.
