:root {
  --color-primary: #2563eb;
  --color-primary-light: #3b82f6;
  --color-secondary: #64748b;
  --color-success: #10b981;
  --color-warning: #f59e0b;
  --color-danger: #ef4444;
  --color-background: #f8fafc;
  --color-surface: #ffffff;
  --color-border: #e2e8f0;
  --color-text: #1e293b;
  --color-text-muted: #64748b;
  --border-radius: 8px;
  --shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
  --transition: all 0.2s ease-in-out;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.6;
  color: var(--color-text);
  background-color: var(--color-background);
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1rem;
}

/* Header */
.header {
  background: linear-gradient(135deg, var(--color-primary) 0%, var(--color-primary-light) 100%);
  color: white;
  padding: 1.5rem 0;
  box-shadow: var(--shadow);
}

.header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 1rem;
}

.header__title {
  font-size: 1.75rem;
  font-weight: 700;
  margin: 0;
}

.header__controls {
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
}

/* Buttons */
.btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: var(--border-radius);
  font-size: 0.875rem;
  font-weight: 500;
  text-decoration: none;
  cursor: pointer;
  transition: var(--transition);
  white-space: nowrap;
}

.btn--sm {
  padding: 0.375rem 0.75rem;
  font-size: 0.8rem;
}

.btn--secondary {
  background: rgba(255, 255, 255, 0.2);
  color: white;
}

.btn--secondary:hover {
  background: rgba(255, 255, 255, 0.3);
}

.btn--outline {
  background: transparent;
  color: white;
  border: 1px solid rgba(255, 255, 255, 0.3);
}

.btn--outline:hover {
  background: rgba(255, 255, 255, 0.1);
  border-color: rgba(255, 255, 255, 0.5);
}

.btn-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0.5rem;
  border: none;
  background: transparent;
  border-radius: var(--border-radius);
  cursor: pointer;
  transition: var(--transition);
}

.btn-icon:hover {
  background-color: var(--color-border);
}

/* Main Content */
.main {
  padding: 2rem 0;
}

/* Cards */
.card {
  background: var(--color-surface);
  border-radius: var(--border-radius);
  border: 1px solid var(--color-border);
  box-shadow: var(--shadow);
  margin-bottom: 1.5rem;
}

.card__header {
  padding: 1.25rem;
  border-bottom: 1px solid var(--color-border);
}

.card__body {
  padding: 1.25rem;
}

/* Progress Overview */
.progress-overview h2 {
  margin-bottom: 1rem;
  color: var(--color-text);
  font-size: 1.25rem;
}

.progress-bar-container {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1rem;
}

.progress-bar {
  flex: 1;
  height: 12px;
  background-color: var(--color-border);
  border-radius: 6px;
  overflow: hidden;
}

.progress-bar__fill {
  height: 100%;
  background: linear-gradient(90deg, var(--color-success) 0%, var(--color-primary) 100%);
  transition: width 0.3s ease;
  width: 0%;
}

.progress-percentage {
  font-weight: 600;
  font-size: 1.1rem;
  color: var(--color-primary);
  min-width: 4rem;
}

.progress-stats {
  display: flex;
  justify-content: space-between;
  font-size: 0.875rem;
  color: var(--color-text-muted);
}

/* Search */
.search-section {
  margin-bottom: 2rem;
}

.form-group {
  margin-bottom: 1rem;
}

.form-control {
  width: 100%;
  padding: 0.75rem;
  border: 1px solid var(--color-border);
  border-radius: var(--border-radius);
  font-size: 1rem;
  transition: var(--transition);
}

.form-control:focus {
  outline: none;
  border-color: var(--color-primary);
  box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}

/* Topic Sections */
.topic-section {
  margin-bottom: 1rem;
}

.topic-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  cursor: pointer;
  transition: var(--transition);
  padding: 1rem 1.25rem;
}

.topic-header:hover {
  background-color: #f9fafb;
}

.topic-header__left {
  display: flex;
  align-items: center;
  gap: 1rem;
  flex: 1;
}

.topic-header__right {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.topic-toggle {
  color: var(--color-secondary);
}

.topic-toggle[aria-expanded="true"] .chevron-icon {
  transform: rotate(90deg);
}

.chevron-icon {
  transition: transform 0.2s ease;
  width: 20px;
  height: 20px;
}

.topic-info {
  flex: 1;
}

.topic-title {
  font-size: 1.125rem;
  font-weight: 600;
  margin-bottom: 0.25rem;
  color: var(--color-text);
}

.topic-description {
  font-size: 0.875rem;
  color: var(--color-text-muted);
  margin: 0;
}

.progress-indicator {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.25rem;
}

.progress-circle {
  position: relative;
  width: 40px;
  height: 40px;
}

.progress-ring {
  transform: rotate(-90deg);
}

.progress-ring__circle {
  stroke: var(--color-primary);
  stroke-dasharray: 113;
  stroke-dashoffset: 113;
  transition: stroke-dashoffset 0.3s ease;
}

.progress-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 0.65rem;
  font-weight: 600;
  color: var(--color-primary);
}

.progress-stats-small {
  font-size: 0.75rem;
  color: var(--color-text-muted);
}

/* Topic Content */
.topic-content {
  border-top: 1px solid var(--color-border);
  padding: 0;
}

.subtopics-list {
  padding: 0;
}

.subtopic-item {
  padding: 1rem 1.25rem;
  border-bottom: 1px solid #f1f5f9;
  transition: var(--transition);
}

.subtopic-item:last-child {
  border-bottom: none;
}

.subtopic-item:hover {
  background-color: #fafbfc;
}

.subtopic-item.completed {
  background-color: rgba(16, 185, 129, 0.05);
}

.subtopic-item.completed .subtopic-name {
  text-decoration: line-through;
  color: var(--color-text-muted);
}

.subtopic-header {
  margin-bottom: 0.75rem;
}

.checkbox-label {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
  cursor: pointer;
  font-size: 0.95rem;
}

.checkbox-label input[type="checkbox"] {
  position: absolute;
  opacity: 0;
  pointer-events: none;
}

.checkbox-custom {
  width: 18px;
  height: 18px;
  border: 2px solid var(--color-border);
  border-radius: 3px;
  background: var(--color-surface);
  transition: var(--transition);
  position: relative;
  flex-shrink: 0;
  margin-top: 2px;
}

.checkbox-label input[type="checkbox"]:checked + .checkbox-custom {
  background: var(--color-success);
  border-color: var(--color-success);
}

.checkbox-label input[type="checkbox"]:checked + .checkbox-custom::after {
  content: '✓';
  position: absolute;
  color: white;
  font-size: 12px;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.subtopic-name {
  flex: 1;
  font-weight: 500;
}

.subtopic-comments {
  margin-left: 2.5rem;
}

.subtopic-comments textarea {
  width: 100%;
  min-height: 60px;
  padding: 0.5rem;
  border: 1px solid var(--color-border);
  border-radius: var(--border-radius);
  font-size: 0.875rem;
  resize: vertical;
  transition: var(--transition);
}

.subtopic-comments textarea:focus {
  outline: none;
  border-color: var(--color-primary);
  box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}

.text-muted {
  color: var(--color-text-muted);
  font-size: 0.75rem;
  margin-top: 0.25rem;
  display: block;
}

/* Footer */
.footer {
  margin-top: 3rem;
  padding-top: 2rem;
  border-top: 1px solid var(--color-border);
}

.footer-content {
  text-align: center;
  color: var(--color-text-muted);
  font-size: 0.875rem;
}

.footer-content p {
  margin-bottom: 0.5rem;
}

.footer-links a {
  color: var(--color-primary);
  text-decoration: none;
}

.footer-links a:hover {
  text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
  .header .container {
    flex-direction: column;
    align-items: stretch;
    gap: 1rem;
  }

  .header__controls {
    justify-content: center;
  }

  .topic-header {
    flex-direction: column;
    align-items: stretch;
    gap: 1rem;
  }

  .topic-header__right {
    justify-content: center;
  }

  .progress-bar-container {
    flex-direction: column;
    align-items: stretch;
    gap: 0.5rem;
  }

  .progress-percentage {
    text-align: center;
  }

  .progress-stats {
    flex-direction: column;
    text-align: center;
    gap: 0.25rem;
  }
}

@media (max-width: 480px) {
  .container {
    padding: 0 0.75rem;
  }

  .header__title {
    font-size: 1.5rem;
  }

  .card__header,
  .card__body {
    padding: 1rem;
  }

  .subtopic-item {
    padding: 0.75rem 1rem;
  }

  .subtopic-comments {
    margin-left: 1.75rem;
  }
}
