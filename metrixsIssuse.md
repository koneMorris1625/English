[metrics/source/plugin/wakatime](https://github.com/lowlighter/metrics/tree/master/source/plugins/wakatime)
Hi, thanks to your amazing works, I deployed my README.md successfully. But there still some confused me. 
When I used **the last option** `.user.login`, `metrics.plugin.wakatime.svg` always told me: `API returned 404`; but if I make `plugin_wakatime_user: current`, the default one, it's working. So could you tell me why use it `.user.login`?

```markdown
#### ℹ️ Examples workflows

[➡️ Available options for this plugin](metadata.yml)

    ```yaml
    - uses: lowlighter/metrics@latest
    with:
        # ... other options
        plugin_wakatime: yes
        plugin_wakatime_token: ${{ secrets.WAKATIME_TOKEN }}      # Required
        plugin_wakatime_days: 7                                   # Display last week stats
        plugin_wakatime_sections: time, projects, projects-graphs # Display time and projects sections, along with projects graphs
        plugin_wakatime_limit: 4                                  # Show 4 entries per graph
        plugin_wakatime_url: https://wakatime.com                 # Wakatime url endpoint
        ➡️ plugin_wakatime_user: .user.login                         # User  
    ```
```
Another bothers me is that the branch. Once workflow general one branch. 
I wish my poor English make your know all above. Thanks for your did!
