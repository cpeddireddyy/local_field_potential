# List of Data Inputs to Run LFP Analysis

- `channel_mapping.xlsx` - (Default) Excel file with the channel mapping for the LFP data.


- `events.xlsx` - Contains the following columns:
  - `file_path` - Path to the *.h5 file.
  - `start_frame` - Start time of the event.
  - `stop_frame` - Stop time of the event.
  - `tracked_subject` - Name of the subject being tracked.
  - `in_video_subject` - Name of the subject in the video.
  - `box_number` - Box number.
  - `notes` - Event notes.


- `labels.xlsx` - Contains the following columns:
  - `tracked_subject` - (List) Name of the subject being tracked.
  - `box_number` - Box number.
  - `sleap_name` - Name of sleap *.h5 file.
  - `current_subject` - Name of the subject in the video.
  - `tone_start_frame` - Start time of the tone.
  - `tone_stop_frame` - Stop time of the tone.
  - `condition` - Condition of the subject (id).
  - `competition_class` - Competition class of the subject (see encoding dict)
  - `notes` - Event notes.
  - `session_dir` - Directory of the session (containing *.rec)
  - `all_subjects` - (List) All subjects in the video.
  - `tone_start_timestamp` - Start time of the tone (timestamp).
  - `tone_stop_timestamp` - Stop time of the tone (timestamp).
  - `trial_label` - Label of the trial (win, loss, rewarded, omission).