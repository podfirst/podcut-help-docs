# Common Issues & Solutions

Quick solutions to common problems you might encounter in Podcut.

## Upload Issues

### Upload Stuck or Frozen

**Symptoms**: Upload progress bar not moving, stuck at same percentage.

**Solutions**:
1. **Check internet connection**
   - Test speed at speedtest.net
   - Need 5+ Mbps upload minimum
   - WiFi? Try ethernet cable

2. **Refresh the page**
   - Reload browser
   - Upload should resume automatically
   - Progress persists across refreshes

3. **Re-upload if needed**
   - Cancel stuck upload
   - Wait 1 minute
   - Start upload again

4. **Check file size/format**
   - Max file size: Check your plan
   - Supported formats: MP4, MOV, AVI, MKV
   - Corrupt file? Try re-exporting

### Upload Fails Immediately

**Symptoms**: Upload starts but fails within seconds.

**Solutions**:
1. **Verify file format**
   - Must be video file
   - Check file extension
   - Try converting to MP4

2. **Check file isn't corrupted**
   - Can you play it locally?
   - Try opening in VLC
   - Re-export from editing software

3. **Check available storage**
   - Account storage full?
   - Settings → Usage
   - Upgrade plan or delete old files

4. **Disable browser extensions**
   - Ad blockers can interfere
   - Try incognito/private mode
   - Disable extensions temporarily

### Slow Upload Speed

**Symptoms**: Upload working but very slow.

**Solutions**:
1. **Close bandwidth-heavy apps**
   - Netflix, YouTube, downloads
   - Other video calls
   - Cloud sync services (Dropbox, Google Drive)

2. **Use ethernet instead of WiFi**
   - Wired connection more stable
   - Faster and more reliable

3. **Upload during off-peak hours**
   - Late night/early morning
   - Less network congestion
   - Your ISP may throttle during peak

4. **Check your internet plan**
   - Know your upload speed limit
   - ISPs often have slow upload (5-10 Mbps common)
   - Consider upgrading plan

## Transcription Issues

### Transcription Taking Too Long

**Symptoms**: Transcript stuck in "Running" status for 20+ minutes.

**Solutions**:
1. **Normal processing times**
   - 30 min audio = ~5 min processing
   - 1 hour audio = ~10 min processing
   - 2 hour audio = ~20 min processing

2. **Check status**
   - Refresh page
   - Check "Last updated" time
   - If over 30 min, might be stuck

3. **Contact support if stuck**
   - Beyond normal time
   - Status not changing
   - We can restart processing

### Poor Transcription Accuracy

**Symptoms**: Many words wrong, nonsense text, missing words.

**Solutions**:
1. **Audio quality is key**
   - Use better microphone
   - Record in quiet environment
   - Speak clearly, moderate pace

2. **Check language setting**
   - Correct language selected?
   - Wrong language = gibberish
   - Re-transcribe with correct language

3. **Edit manually**
   - Transcript tab → Edit Mode
   - Click text to edit
   - Fix critical errors
   - Don't stress over every word

4. **Accept AI limitations**
   - 85-95% accuracy typical
   - Better audio = better results
   - Proper nouns often wrong (edit those)

### Speakers Not Identified Correctly

**Symptoms**: Speaker 0 and Speaker 1 mixed up, or too many speakers detected.

**Solutions**:
1. **Expected behavior**
   - AI guesses at speakers
   - Not always perfect
   - Especially similar voices

2. **Edit speaker names**
   - Transcript tab → Edit Mode
   - Click speaker name
   - Type real name
   - Updates throughout transcript

3. **Manually reassign if needed** (coming soon)
   - Select segment
   - Change speaker assignment
   - Fixes misattributions

4. **Improve recording for next time**
   - Distinct voices
   - Less cross-talk
   - Better audio separation

### Transcription Failed

**Symptoms**: Status shows "Failed" with error message.

**Solutions**:
1. **Read error message**
   - Tells you what went wrong
   - Common: No audio track, unsupported format

2. **Check audio track exists**
   - Does video have audio?
   - Play it locally to verify
   - Silent video can't be transcribed

3. **Re-transcribe**
   - ⋮ menu → "Re-transcribe"
   - Starts fresh attempt
   - May succeed on retry

4. **Contact support**
   - If repeatedly failing
   - Send us episode ID
   - We'll investigate

## Processing Issues (Clips, Highlights)

### Clip Processing Failed

**Symptoms**: Clip status shows "Failed" with error.

**Solutions**:
1. **Check error message**
   - Specific reason shown
   - Common: Invalid time range, source missing

2. **Verify time range**
   - Start time < end time?
   - Both within video duration?
   - Not before 0 or after video end

3. **Check source video available**
   - Episode processed successfully?
   - Video playable?
   - Try refreshing episode

4. **Try again**
   - Delete failed clip
   - Create new one
   - May succeed on retry

5. **Simplify settings**
   - Disable crop
   - Disable captions
   - Process first, then try with features

### Clip Processing Stuck

**Symptoms**: Clip shows "Processing" for 10+ minutes.

**Solutions**:
1. **Normal processing times**
   - 30-60 sec clip = 1-3 min processing
   - Longer clips = longer processing
   - Crop + captions = adds time

2. **Refresh page**
   - Status updates automatically
   - Refresh to be sure
   - Check timestamp of last update

3. **Check server status** (coming soon)
   - Status page link
   - Known issues?
   - Scheduled maintenance?

4. **Wait a bit longer**
   - Server load varies
   - May just be slow queue
   - Give it 15-20 min total

5. **Contact support**
   - If truly stuck beyond 30 min
   - Send clip ID
   - We can investigate

### AI Highlight Generation Failed

**Symptoms**: Highlight generation job shows "Failed".

**Solutions**:
1. **Check transcript exists**
   - AI highlights use transcript
   - Must transcribe first
   - Transcript successful?

2. **Check video duration**
   - Very short videos (< 3 min) may not work
   - Need enough content for highlights

3. **Try again**
   - May be temporary issue
   - Generate → Retry

4. **Create highlights manually**
   - Fallback option
   - Use transcript Highlight Mode
   - Still faster than no assistance

## Playback Issues

### Video Won't Play

**Symptoms**: Black screen, spinning loader, or error message.

**Solutions**:
1. **Check video processed successfully**
   - Episode status "Completed"?
   - Thumbnail visible?
   - If still processing, wait

2. **Refresh the page**
   - Browser cache issue
   - Hard refresh: Cmd/Ctrl + Shift + R

3. **Try different browser**
   - Chrome recommended
   - Test in Firefox or Edge
   - Rules out browser-specific issue

4. **Check internet connection**
   - Streaming requires stable connection
   - Test other videos (YouTube)
   - Slow connection = buffering

5. **Clear browser cache**
   - Settings → Privacy → Clear cache
   - Close and reopen browser
   - Try again

### Video Playback Choppy/Stuttering

**Symptoms**: Video plays but skips frames, audio out of sync.

**Solutions**:
1. **Close other tabs/apps**
   - Browser using too much memory
   - Close unused tabs
   - Close heavy applications

2. **Check CPU usage**
   - Task Manager (Windows) or Activity Monitor (Mac)
   - Podcut using excessive CPU?
   - Other apps hogging resources?

3. **Lower video quality** (coming soon)
   - Switch to lower resolution
   - Reduces bandwidth and CPU needs

4. **Try different browser**
   - Some browsers better than others
   - Chrome generally fastest

5. **Update browser**
   - Outdated browser = poor performance
   - Update to latest version
   - Restart browser after update

### Audio Out of Sync with Video

**Symptoms**: Lips don't match audio, lag between visual and sound.

**Solutions**:
1. **Refresh the page**
   - Most common fix
   - Hard refresh: Cmd/Ctrl + Shift + R

2. **Check source video**
   - Play original file locally
   - Was it in sync originally?
   - If not, re-export properly

3. **Re-upload if needed**
   - If original is fine but Podcut version isn't
   - Upload new version
   - Contact support if persists

## Interface/UI Issues

### Page Not Loading

**Symptoms**: Blank page, infinite loading, error screen.

**Solutions**:
1. **Check internet connection**
   - Lost connection?
   - Test other websites

2. **Refresh page**
   - Cmd/Ctrl + R
   - Or hard refresh: Cmd/Ctrl + Shift + R

3. **Clear browser cache**
   - Settings → Clear browsing data
   - Check "Cached images and files"
   - Try again

4. **Try incognito/private mode**
   - Rules out extension conflicts
   - Rules out cache issues

5. **Check browser console** (for tech-savvy users)
   - F12 → Console tab
   - Red errors? Screenshot and send to support

### Changes Not Saving

**Symptoms**: Edit something, but reverts when you refresh.

**Solutions**:
1. **Check for save confirmation**
   - Look for success message
   - "Saved" indicator
   - If no confirmation, didn't save

2. **Check internet connection**
   - Lost connection = no save
   - Changes saved when online only

3. **Try again**
   - Make change
   - Wait for confirmation
   - Refresh to verify

4. **Check permissions**
   - Do you have edit access?
   - Viewers can't save changes
   - Owner/Editor permission needed

### Can't Find Something

**Symptoms**: Episode, clip, or feature seems missing.

**Solutions**:
1. **Check correct project**
   - Episodes organized by project
   - Switch projects in sidebar

2. **Use search**
   - Search bar in top
   - Type episode name
   - Shows all matches

3. **Check filters**
   - Filters active?
   - "Show all" to clear filters
   - Clip status filter may hide items

4. **Check tab**
   - Right tab selected?
   - Clips in Clips tab, Highlights in Highlights tab

## Desktop App Issues

### App Won't Launch

**Symptoms**: Double-click, nothing happens.

**Solutions**:
1. **Check system requirements**
   - macOS 10.15+ or Windows 10+
   - Sufficient RAM (8GB+)
   - Disk space available

2. **Restart computer**
   - Simple but effective
   - Clears system issues

3. **Reinstall app**
   - Uninstall completely
   - Download fresh installer
   - Install again

4. **Check security settings**
   - macOS: System Preferences → Security
   - Windows: Antivirus blocking?
   - Allow Podcut

### Camera Not Working

**Symptoms**: Black screen in camera preview.

**Solutions**:
1. **Check camera connected**
   - USB plugged in firmly
   - Try different USB port
   - Camera working in other apps?

2. **Grant camera permission**
   - macOS: System Preferences → Security → Camera
   - Windows: Settings → Privacy → Camera
   - Enable for Podcut

3. **Restart app**
   - Quit completely
   - Relaunch
   - Camera may initialize

4. **Update drivers** (Windows)
   - Device Manager
   - Update camera driver
   - Restart computer

### Microphone Not Working

**Symptoms**: No audio levels, silence.

**Solutions**:
1. **Check microphone connected**
   - USB plugged in
   - Try different port
   - Test in system settings

2. **Grant microphone permission**
   - macOS: System Preferences → Security → Microphone
   - Windows: Settings → Privacy → Microphone
   - Enable for Podcut

3. **Select correct input**
   - Settings → Audio
   - Select microphone from dropdown
   - Multiple mics? Choose right one

4. **Check input volume**
   - System audio settings
   - Input level turned up?
   - Not muted?

5. **Test in other apps**
   - Works elsewhere?
   - If yes, Podcut issue (contact support)
   - If no, hardware/OS issue

## Performance Issues

### Podcut Running Slowly

**Symptoms**: UI laggy, clicks delayed, general sluggishness.

**Solutions**:
1. **Close other tabs**
   - Each tab uses memory
   - Close what you don't need

2. **Close other apps**
   - Free up system resources
   - Especially memory-heavy apps

3. **Restart browser**
   - Fresh start
   - Clears memory leaks

4. **Check system resources**
   - Task Manager/Activity Monitor
   - Low memory? Close apps or upgrade RAM
   - High CPU? What's using it?

5. **Update browser**
   - Latest version has performance improvements

### High Memory Usage

**Symptoms**: Computer slowing down, browser using lots of RAM.

**Solutions**:
1. **Long video files use more memory**
   - Expected for large videos
   - 4K video = more memory than 1080p

2. **Close episode when done**
   - Frees up memory
   - Open only what you need

3. **Upgrade RAM** (if frequently hitting limit)
   - 8GB minimum
   - 16GB recommended for heavy use

4. **Use smaller videos**
   - 1080p instead of 4K
   - Compress if possible

## Still Need Help?

If you've tried these solutions and still experiencing issues:

### Contact Support

**Email**: support@podfirst.com

**Include**:
- Description of issue
- Steps to reproduce
- Screenshots if applicable
- Browser and OS version
- Episode ID (if relevant)

**Response Time**:
- Typically within 24 hours
- Urgent issues prioritized

### Check Status Page

(Coming Soon)
- Known issues posted
- Scheduled maintenance
- Service status

### Community Forum

(Coming Soon)
- Ask other users
- Share solutions
- Feature discussions

---

**Most issues have simple fixes - try the common solutions first!** 🔧
