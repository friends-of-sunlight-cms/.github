# Rules for Plugin Developers in the Friends of Sunlight CMS Organization *(FoSC)*

## 1. Credits
- Credits for plugin development always belong to the original developer(s).

## 2. Repository Availability
- Repositories for plugins, templates, or translations published under the *FoSC* organization will remain permanently accessible.
- If a repository is no longer actively developed, it will receive basic maintenance to ensure compatibility with the system.
- If a plugin becomes obsolete *(e.g., its functionality is directly implemented into the system)*, it will be archived but still accessible.

## 3. Publishing Rules
### Mandatory Rules
- The repository name **MUST** include a suffix according to the plugin’s purpose, such as: `-plugin`, `-template`, `-language`. For example: `mydesign-template` or `pirate-language`.
- The plugin ZIP release **MUST** be compatible with the plugin installer in the administration panel and therefore have the following structure:  
  - `plugins/`*`<extemd | languages | templates>`*`/<myplugin>`.

### Recommendations
- It is **strongly recommended** to structure the repository in the same way to facilitate the use of the *FoSC* release creation tool.

*The tool automatically installs dependencies and creates ZIP archives compatible with the Sunlight CMS system (in the future, it may also enable automatic releases via the GitHub API).*

## 4. Request for Inclusion on the Official Website
- Developers **MAY** request to have their plugin included in the `Plugins` section on the official Sunlight CMS website.

## 5. Repository Archiving
- An abandoned repository **MAY** be archived upon request by the original developer.
- Archived or abandoned repositories **MAY** be further developed by another *FoSC* member, usually in the form of a fork.

## 6. Security and Community Integrity
- A plugin that intentionally compromises the security of the system, the community, or end users will be removed from the *FoSC* organization and the official website *(if listed there)* without prior notice.

## 7. Collaboration and Development
- *FoSC* encourages collaboration in development. Members **MAY** contribute to the development of plugins, including those created by others, as long as they follow the rules and respect the credits of the original developer.
- For significant modifications to someone else’s non-abandoned plugin *(e.g., a new feature or a bug fix requiring major changes)*, a Pull Request (PR) must be submitted to the original repository.
- This rule does not apply to simple updates for compatibility with new Sunlight CMS versions or minor bug fixes *(hotfixes)*.

## 8. Licensing
- All plugins published under *FoSC* must use an open-source license compatible with the philosophy of Sunlight CMS. The license **MUST** be clearly stated in the repository.

## 9. Communication and Dispute Resolution
- Developers are encouraged to maintain clear communication with the community and other contributors.
- In the event of disputes regarding repository ownership, development direction, or other matters, *FoSC* moderators/administrators will act as mediators to find a fair resolution.

## 10. Removal or Transfer of Plugins
- If a developer wishes to transfer a plugin out of the *FoSC* organization, they **MAY** request this, provided it does not disrupt the stability or security of the community, and any changes or activities do not compromise the trust or functionality of the *FoSC* community.
- Derived *(forked)* versions of plugins may exist under a new name, even if the original repository is removed. However, the author **MAY** request that it is clearly stated in the fork that the plugin is based on their work if the code matches more than 70%.

## 11. Rule Compliance
- Developers **are required** to comply with these rules and any additional guidelines published by the *FoSC* organization.

Participation in the *FoSC* community **is voluntary**, but developers commit to adhering to these rules to foster a supportive, collaborative, and secure environment for all contributors and users.

