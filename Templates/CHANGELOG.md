## **IMPORTANT: PROJECT CONTINUITY**  
To maintain project context across conversations, always start a new chat with the following instructions:  

```
You are working on the (project name here)
Read CHANGELOG.md and PROJECT_SCOPE.md now, report your findings, and strictly follow all instructions found in these documents.  
You must complete the check-in process before proceeding with any task.  

Begin check-in process and document analysis.
```

---

## **IMPORTANT: SELF-MAINTENANCE INSTRUCTIONS**

### **Before Taking Any Action or Making Suggestions**  
1. **Read Both Files**:  
   - Read `CHANGELOG.md` and `PROJECT_SCOPE.md`.  
   - Briefly report:  
     ```
     Read [filename]: [key points relevant to current task]
     ```

2. **Review Context**:  
   - Assess existing features, known issues, and architectural decisions.

3. **Inform Responses**:  
   - Use the gathered context to guide your suggestions or actions.

4. **Proceed Only After Context Review**:  
   - Ensure all actions align with the project’s scope and continuity requirements.

---

### **After Making ANY Code Changes**  
1. **Update Documentation Immediately**:  
   - Add new features/changes to the `[Unreleased]` section of `CHANGELOG.md`.  
   - Update `PROJECT_SCOPE.md` if there are changes to architecture, features, or limitations.

2. **Report Documentation Updates**:  
   - Use the following format to report updates:  
     ```
     Updated CHANGELOG.md: [details of what changed]  
     Updated PROJECT_SCOPE.md: [details of what changed] (if applicable)
     ```

3. **Ensure Alignment**:  
   - Verify that all changes align with existing architecture and features.

4. **Document All Changes**:  
   - Include specific details about:
     - New features or improvements
     - Bug fixes
     - Error handling changes
     - UI/UX updates
     - Technical implementation details

---

### **Documentation Update Protocol**
1. **Never Skip Documentation Updates**:  
   - Always update documentation, even for minor changes.

2. **Update Before Responding to the User**:  
   - Ensure documentation is complete before providing feedback or solutions.

3. **For Multiple Changes**:
   - Document each change separately.
   - Maintain chronological order.
   - Group related changes together.

4. **For Each Feature/Change, Document**:
   - What was changed.
   - Why it was changed.
   - How it works.
   - Any limitations or considerations.

5. **If Unsure About Documentation**:
   - Err on the side of over-documenting.
   - Include all relevant details.
   - Maintain consistent formatting.

---

### **Log Analysis Protocol**
1. **When Reviewing Conversation Logs**:
   - Briefly report findings using this format:  
     ```
     Analyzed conversation: [key points relevant to task]
     ```

2. **When Examining Code or Error Logs**:
   - Report findings using this format:  
     ```
     Reviewed [file/section]: [relevant findings]
     ```

3. **Include Minimal Context for Current Task**:
   - Ensure findings directly inform the current task at hand.

---

### **Critical Notes**
- This read-first, write-after approach ensures consistency and continuity across conversations.
- Documentation updates and log analysis reports are mandatory and must be completed before responding to the user.

---

## [Unreleased]

### Changed
[Document all changes here.]
