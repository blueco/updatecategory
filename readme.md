## Setup notes
1. Download the folder and upload the WordPress plugin folder i.e wp-content/plugins.
2. On WordPress Dashboard go to Plugins i.e wp-admin/plugins.php and activate plugin name Update Category.

## Work left in progress
1. The Bonus part in the test - Disable ability to add new categories from within WordPress.

## Some notes about the test
1. The test was not complicated but good enough to test the thinking and level of understanding of wordpress codex/PHP.
2. Category tags/term id have a different approach of updating which requires a slightly extended coding - I believe.
3. Given the right environment and resources I will be able to find answer to some questions along the completion of this plugin.

## Time taken to complete
1. I have to appologise to examiner and person viewing this code, myself and kids was sick and down with terrible flu. Took medicine and drowsy.
2. My replied on the test was a total crap.
3. After I got better 2 days later, I revisit the test and did some research.
4. About 5 hours taken to complete the plugin.

## Notes to examiner
1. Thank you for your time for viewing/validating.
2. It's a pleasure to be able to take this test.
3. Looking forward to meet the examiner of this plugin and chances to work together.

## Dev Notes
1. This plugin work based on the db.json file available within the folder. OR the following

{
  "categories": [
    {
      "id": 256,
      "name": "State1",
      "parent_id": null
    },
    {
      "id": 261,
      "name": "NSW",
      "parent_id": 247
    },
    {
      "id": 257,
      "name": "VIC",
      "parent_id": 247
    },
    {
      "id": 262,
      "name": "QLD",
      "parent_id": 247
    },
    {
      "id": 258,
      "name": "WA",
      "parent_id": 247
    },
    {
      "id": 260,
      "name": "ACT",
      "parent_id": 247
    },
    {
      "id": 255,
      "name": "National",
      "parent_id": null
    },
    {
      "id": 259,
      "name": "World",
      "parent_id": null
    }
  ]
}
