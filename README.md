# x-user-script-manager
X is a simple and effective user script manager for UNIX and Bash Environments

## Installation

   git clone https://github.com/mcisback/x-user-script-manager.git

   cd x-user-script-manager
   
   ./x install

## Usage
Usage:

	~/.x/.bin/x <cmd> [<args>]
		run_script|r: Run a X script (arg: <script_name>)
		create_script|c: Create a X script (args: <script_name> <template>)
		list_templates|lt: List templates available in ~/.x
		list_scripts|ls: List scripts available in ~/.x
		show_template|t: Show Template content (arg: <template_name>)
		show_script|s: Show Script content (arg: <script_name>)
		show_trash|st: Show Trash located in ~/.x/trash
		edit_script|e: Edit script, if exists (arg: <script_name>
		delete_script|d: Delete a script by copying it to ~/.x/trash (arg: <script_name>)
		generate_completions|gc: Generate complentions file
		install|i: Install this script (To run just the first time)
		x_reduplicate|x: Duplicate X and copy it  to ~/.x/.bin
		x_autoedit|ae: Edit X:~/.x/.bin/x
		x_backup|xb: Backup X Script and copy it to $X_BACKUP_DIR:~/Dropbox/X_BACKUP
		print_bashrc_conf|pbc: Print Lines to add to ~/.bashrc
		help|h: Print this help

