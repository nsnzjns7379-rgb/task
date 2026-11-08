// 1. هيكلة بيانات الطالب (Class & Constructor)
class Student {
    constructor(id, name, grades, attendance) {
        this.id = id;
        this.name = name;
        this.grades = grades; // مصفوفة تحتوي على 3 درجات
        this.attendance = attendance; // نسبة الحضور
    }

    // 2. دالة حساب المتوسط ( باستخدام reduce )
    calculateAverage() {
        const sum = this.grades.reduce((total, current) => total + current, 0);
        return sum / this.grades.length;
    }

    // دالة التقدير بناءً على المتوسط
    getGradeLetter(avg) {
        if (avg >= 90) return 'A';
        if (avg >= 80) return 'B';
        if (avg >= 70) return 'C';
        if (avg >= 60) return 'D';
        if (avg >= 50) return 'E';
        return 'F';
    }

    // دالة النتيجة النهائية (ناجح / يحتاج مراجعة)
    getFinalResult() {
        const avg = this.calculateAverage();
        if (avg >= 50 && this.attendance >= 75) {
            return "ناجح";
        } else {
            return "يحتاج مراجعة";
        }
    }
}

// 3. نظام تشغيل الجامعة (Objects Array) - 4 طلاب (مع وجود متعثرين بين 40 و 49)
const studentsList = [
    new Student(1, "أحمد محمد", [85, 90, 88], 90),
    new Student(2, "سارة علي", [42, 45, 44], 80), // متعثر (متوسطه بين 40 و 49)
    new Student(3, "محمود خالد", [60, 65, 70], 70),
    new Student(4, "منى أحمد", [46, 48, 47], 85)  // متعثر (متوسطه بين 40 و 49)
];

console.log("--- تقرير أداء الطلاب بالكامل ---");
studentsList.forEach(student => {
    const avg = student.calculateAverage();
    console.log(`الاسم: ${student.name} | المتوسط: ${avg.toFixed(2)} | التقدير: ${student.getGradeLetter(avg)} | النتيجة: ${student.getFinalResult()}`);
});


// 4. لجنة الرأفة (Array Methods)
// أ. الاستخراج (filter) للطلاب المتعثرين الذين متوسطاتهم بين 40 و 49
const strugglingStudents = studentsList.filter(student => {
    const avg = student.calculateAverage();
    return avg >= 40 && avg < 50;
});

// ب. المعالجة (map) لإضافة 5 درجات رأفة لمتوسطاتهم
const updatedStrugglingAverages = strugglingStudents.map(student => {
    let newAvg = student.calculateAverage() + 5;
    return { name: student.name, newAverage: newAvg };
});

console.log("\n--- الطلاب المتعثرين بعد تطبيق درجات الرأفة (+5) ---");
console.log(updatedStrugglingAverages);

// ج. التحليل (reduce) لجمع المتوسطات الجديدة بعد التعديل
const totalNewAverages = updatedStrugglingAverages.reduce((sum, item) => sum + item.newAverage, 0);

// د. متوسط الرأفة (مع درع حماية لمنع القسمة على صفر)
const count = updatedStrugglingAverages.length;
const overallGraceAverage = count > 0 ? (totalNewAverages / count) : 0;

console.log(`\nالمتوسط العام للمتعثرين بعد الرأفة: ${overallGraceAverage.toFixed(2)}`);
