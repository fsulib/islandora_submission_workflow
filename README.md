# islandora_submission_workflow
Set up workflows for handling submissions that turn into Islandora objects

# Goals
- Create an easy to use interface for non-admins to submit multiple types of objects
- Create default workflows/forms for admins to use out of the box, but make them flexible
- Allow admins to create unlimited bundles and workflows to support obscure use cases
- Use D7 tools and methods that map easily to D8 (CLAW submission workflow beta)

# To Do
- Create module skeleton,require workflow & friends
- Create example content type w/ mapped fields (?)
- programmatically create a workflow rule action for creating new Islandora object
  - Destination collection driven by tokens
  - MODS record created via twig template + tokens
  - Update node to include PID
  - Could also include rules to update/delete Islandora objects
- create example workflow
