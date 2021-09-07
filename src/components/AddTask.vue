<template>
    <form class="add-form">
        <div class="form-control">
            <label>Task</label>
            <input type="text" name="text" placeholder="Add task">
        </div>
        <div class="form-control">
            <label>Day & Time</label>
            <input type="text" name="day" placeholder="Add Day & Time">
        </div>
        <div class="form-control form-control-check">
            <label>Reminder</label>
            <input type="checkbox" name="reminder" value="Save Task">
        </div>
        <input type="submit" value="Save Task" class="btn btn-block">
    </form>
</template>
<script>
export default {
    name: "AddTask",
}
</script>